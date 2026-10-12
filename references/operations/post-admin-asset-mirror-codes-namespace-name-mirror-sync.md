# POST /admin/asset/mirror/codes/{namespace}/{name}/mirror/sync

**Resource:** [Admin Asset Mirror](../resources/Admin-Asset-Mirror.md)
**Synchronize a repository mirror for administration**
**Operation ID:** `post--admin-asset-mirror-codes-{namespace}-{name}-mirror-sync`

Requires asset/mirror permission. Source validation and shared business constraints are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | Repository owner name |
| `name` | path | string | Yes | Repository name |

## Request Body

Mirror operation parameters

**Content Types:** `application/json`

**Schema:** [types.SyncMirrorParams](../schemas/types-SyncMirrorParams/types-SyncMirrorParams.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
