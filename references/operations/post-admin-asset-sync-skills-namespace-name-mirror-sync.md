# POST /admin/asset/sync/skills/{namespace}/{name}/mirror/sync

**Resource:** [Admin Asset Sync](../resources/Admin-Asset-Sync.md)
**Retry repository synchronization from multi-source synchronization administration**
**Operation ID:** `post--admin-asset-sync-skills-{namespace}-{name}-mirror-sync`

Requires asset/sync administrator permission. Original repository checks and scheduling behavior are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | Repository owner name |
| `name` | path | string | Yes | Repository name |

## Request Body

Scheduling options

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
