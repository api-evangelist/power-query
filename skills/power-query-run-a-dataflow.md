---
name: power-query-run-a-dataflow
description: >-
  Trigger an on-demand run of a Microsoft Fabric dataflow (Power Query Gen2),
  optionally overriding its parameters, and poll the long-running operation to
  completion.
api: Fabric Power Query Programmatic API
base_url: https://api.fabric.microsoft.com/v1
operations:
  - Items_ListDataflows
  - Items_DiscoverDataflowParameters
  - BackgroundJobs_RunOnDemandExecute
  - BackgroundJobs_RunOnDemandApplyChanges
generated: '2026-08-29'
method: generated
source: openapi/power-query-fabric-dataflow-swagger.json
---

# Run a Power Query dataflow on demand

## Before you start

- You need a Microsoft Entra ID bearer token. Delegated scope for execution is
  `Dataflow.Execute.All` or `Item.Execute.All`.
- Scope alone is not enough. The caller must also hold a Fabric **workspace role**
  on the workspace that owns the dataflow. A 403-shaped `InsufficientPrivileges`
  or `InsufficientWorkspaceRole` means the role is missing, not the token.
- Every request is `Authorization: Bearer <token>`. There are no API keys.

## 1. Find the dataflow

    GET /workspaces/{workspaceId}/dataflows

`Items_ListDataflows`. Requires `Workspace.Read.All` or `Workspace.ReadWrite.All`
— note this is a *workspace* scope, not a dataflow scope.

Optional query params: `recursive` (walk subfolders), `rootFolderId` (scope to one
folder), `continuationToken` (paging).

The response is `{ value: [...], continuationToken?, continuationUri? }`. Keep
following `continuationUri` until neither continuation field is present. Both are
removed from the response when the collection is exhausted — do not treat an empty
string as the end.

## 2. Discover parameters, if you intend to override any

    GET /workspaces/{workspaceId}/dataflows/{dataflowId}/parameters

`Items_DiscoverDataflowParameters`. Scopes: `Dataflow.Read.All`,
`Dataflow.ReadWrite.All`, `Item.Read.All` or `Item.ReadWrite.All`.

Returns a paginated list of typed parameters. The spec declares nine concrete
parameter types (string, boolean, integer, number, dateTime, dateTimeZone, date,
time, duration) — send the value in the shape the parameter declares.

If the dataflow has no parameters this call returns `DataflowNotParametricError`.
That is a normal answer, not a failure: go to step 3 with no `executionData`.

## 3. Start the run

    POST /workspaces/{workspaceId}/dataflows/{dataflowId}/jobs/execute/instances

`BackgroundJobs_RunOnDemandExecute`. The body is optional. To override parameters:

    {
      "executionData": {
        "executeOption": "ApplyChangesIfNeeded",
        "parameters": [
          { "parameterName": "OrderKey", "type": "Automatic", "value": 25 }
        ]
      }
    }

Use `BackgroundJobs_RunOnDemandApplyChanges` at
`.../jobs/applyChanges/instances` instead when you want to apply pending
definition changes rather than execute the flow.

## 4. Poll to completion

Both job operations return **202 Accepted**, never a result. The response carries
a `Location` header naming the job instance. Poll that URL.

- Honour `Retry-After` if it is present.
- Poll on a fixed interval; do not busy-loop. Polling consumes the Long-Running
  Operations quota bucket (200 calls/minute per identity).
- There is **no cancel operation** on this API. Once a run starts you cannot call
  it back — a dataflow run writes to its destination. Confirm the parameter values
  before you POST, not after.

## Failure handling

| errorCode | What to do |
|---|---|
| `ItemNotFound` | Wrong workspaceId/dataflowId, or the item was soft-deleted. |
| `InsufficientPrivileges` | Check the workspace role, not just the scope. |
| `TooManyRequestsForJobs` | Too many on-demand runs. Back off. |
| `InvalidJobType` | The job type segment in the path is wrong. |

On HTTP 429, read `Retry-After` and wait. Fabric publishes no budget headers, so
you cannot see how much quota remains — spread requests evenly across the
60-second window rather than bursting. The quota bucket refills all at once at
the end of the window; it does not recover gradually.

Error bodies are `{ errorCode, message, requestId, moreDetails, isRetriable }`.
Read `isRetriable` before retrying anything, and quote `requestId` in any support
request.
