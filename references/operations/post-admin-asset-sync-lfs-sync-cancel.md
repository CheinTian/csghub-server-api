# POST /admin/asset/sync/lfs_sync/cancel

**Resource:** [Admin Asset Sync](../resources/Admin-Asset-Sync.md)
**Cancel a task from multi-source synchronization administration**
**Operation ID:** `post--admin-asset-sync-lfs_sync-cancel`

Requires asset/sync administrator permission. The request is forwarded to /api/v1/lfs_sync/cancel.

## Request Body

Task to cancel, identified by task_id

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Invalid cancellation request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Synchronization task not found |
| 500 | Cancellation failed |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
