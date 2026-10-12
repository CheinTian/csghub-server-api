# POST /admin/asset/model/models/{namespace}/{name}/mirror/sync

**Resource:** [Admin Asset Model](../resources/Admin-Asset-Model.md)
**Post /models/:namespace/:name/mirror/sync for asset/model administration**
**Operation ID:** `post--admin-asset-model-models-{namespace}-{name}-mirror-sync`

Requires asset/model administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | repo owner name |
| `name` | path | string | Yes | repo name |

## Request Body

scheduling options

**Content Types:** `application/json`

**Schema:** [types.SyncMirrorParams](../schemas/types-SyncMirrorParams/types-SyncMirrorParams.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
