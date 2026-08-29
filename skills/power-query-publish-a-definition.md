---
name: power-query-publish-a-definition
description: >-
  Create a Microsoft Fabric dataflow from a Power Query mashup definition, or
  overwrite an existing one, safely — including the rollback copy the API does not
  keep for you.
api: Fabric Power Query Programmatic API
base_url: https://api.fabric.microsoft.com/v1
operations:
  - Items_CreateDataflow
  - Items_GetDataflowDefinition
  - Items_UpdateDataflowDefinition
  - Items_UpdateDataflow
  - Items_DeleteDataflow
generated: '2026-08-29'
method: generated
source: openapi/power-query-fabric-dataflow-swagger.json
---

# Publish a Power Query definition

## Prerequisites

- Delegated scope `Dataflow.ReadWrite.All` or `Item.ReadWrite.All`.
- The **contributor** workspace role. Microsoft states this explicitly for
  `Items_CreateDataflow`; a token with the right scope and the wrong role fails
  with `InsufficientWorkspaceRole`.
- The workspace must be on a supported Fabric capacity. A trial capacity works;
  a workspace with no capacity does not.

## Create

    POST /workspaces/{workspaceId}/dataflows

`Items_CreateDataflow`. Body is a `CreateDataflowRequest`: `displayName`, optional
`description`, optional `folderId`, and an optional `definition` whose `parts[]`
each carry a `path`, a base64 `payload` and a `payloadType`.

Returns **201** when the dataflow is provisioned inline, or **202** with
`Location`, `x-ms-operation-id` and `Retry-After` when provisioning continues in
the background. Poll `Location`.

`ItemDisplayNameAlreadyInUse` means the name is taken inside that workspace — names
are unique per workspace, not per tenant.

`CorruptedPayload` almost always means the base64 encoding or the `payloadType` of
a definition part is wrong, not that the M is wrong.

### There is no idempotency key

Fabric publishes none for this API. **A retried create makes a second dataflow.**
If a `POST` times out or you lose the response, do not retry blind — call
`Items_ListDataflows` and check for the `displayName` first. Poll the `Location`
you were given rather than re-issuing the create.

## Overwrite an existing definition

    POST /workspaces/{workspaceId}/dataflows/{dataflowId}/getDefinition   # FIRST
    POST /workspaces/{workspaceId}/dataflows/{dataflowId}/updateDefinition

**Always call `Items_GetDataflowDefinition` first and keep the response.** This API
has no version history and no rollback operation. `Items_UpdateDataflowDefinition`
replaces the definition outright; the copy you saved is the only way back.

`updateMetadata` is an optional query flag on the update. Both operations can
return 202 — poll `Location`.

To change only the display name, description or folder, use
`Items_UpdateDataflow` (PATCH) instead — it does not touch the definition.

## Delete — read this before you call it

    DELETE /workspaces/{workspaceId}/dataflows/{dataflowId}
    DELETE /workspaces/{workspaceId}/dataflows/{dataflowId}?hardDelete=true

`hardDelete` omitted or `false` performs a **soft delete**: recoverable.
`hardDelete=true` is **permanent and cannot be recovered** — the spec says so in
those words.

Two things the docs do not give you, and you should not assume:

1. **No retention window is published.** Nothing states how long a soft-deleted
   dataflow stays recoverable. Do not promise a user "you have 30 days".
2. **There is no restore operation in this API.** Recovery happens outside this
   contract, through the Fabric portal.

Soft delete can also be switched off tenant-wide by an admin
(`TenantSwitchDisabled`) or be unavailable for the item type
(`FeatureNotAvailable` / `UnsupportedItemType`). When any of those come back, the
delete you just performed was effectively permanent.

**Never set `hardDelete=true` on behalf of a user without explicit confirmation of
that specific flag.**
