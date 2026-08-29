---
name: power-query-execute-a-query
description: >-
  Execute a Power Query M query against a Microsoft Fabric dataflow and read the
  result, either a named query from the stored definition or a supplied custom
  mashup document.
api: Fabric Power Query Programmatic API
base_url: https://api.fabric.microsoft.com/v1
operations:
  - QueryExecution_ExecuteQuery
generated: '2026-08-29'
method: generated
source: openapi/power-query-fabric-dataflow-swagger.json
---

# Execute a Power Query against a dataflow

This is the closest thing Power Query has to a "run this transformation and give
me the answer" endpoint. It is the only operation on the surface that returns
transformed data rather than item metadata.

## Call

    POST /workspaces/{workspaceId}/dataflows/{dataflowId}/executeQuery

`QueryExecution_ExecuteQuery`.

- Scopes: `Dataflow.Execute.All` or `Item.Execute.All`, plus a Fabric workspace role.
- Optional `Accept` request header selects the result serialization.
- Body is an `ExecuteQueryRequest`: name a query from the dataflow's stored
  definition, or supply a custom mashup document to run instead.

## Hard limits you must design around

- **90 seconds.** Microsoft states verbatim: "Queries can run for a maximum of 90
  seconds." There is no way to raise it from the API. Push filtering and
  aggregation into the query so it folds to the source rather than pulling rows
  back to be shaped.
- **202 Accepted is a normal outcome.** The response may be 200 with the result,
  or 202 with `Location`, `x-ms-operation-id` and `Retry-After`. Handle both. Code
  that only handles 200 will silently drop long-running results.
- Polling counts against the Long-Running Operations quota — 200 calls/minute per
  identity.

## Failure handling

`DataflowExecuteQueryError` is the catch-all for this operation. Microsoft lists
the causes explicitly: the specified query name is invalid or empty, the custom
mashup document is invalid, or the named query was not found in the dataflow (or
in the custom mashup document, if one was supplied). Check the query name against
the dataflow definition before assuming a service problem:

    POST /workspaces/{workspaceId}/dataflows/{dataflowId}/getDefinition

`Items_GetDataflowDefinition` returns the mashup and its parts. Note it needs
`Dataflow.ReadWrite.All` or `Item.ReadWrite.All` — reading a definition requires a
*write* scope on this API, which is easy to get wrong.

## Validate M locally first

`@microsoft/powerquery-parser` (npm, 2.0.0) parses and validates M with no service
call at all. Parse-checking a mashup locally before spending a 90-second execution
window is free and much faster than round-tripping the error.
