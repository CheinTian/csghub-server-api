# POST /sync/client_setting

**Resource:** [Sync](../resources/Sync.md)
**Create sync client setting or update an existing sync client setting**
**Operation ID:** `post--sync-client_setting`

Requires asset/sync administrator permission and a valid license. Creates or updates synchronization settings.

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateSyncClientSettingReq](../schemas/types-CreateSyncClientSettingReq/types-CreateSyncClientSettingReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal server error |

## Security

- **ApiKey**
