# POST /admin/broadcasts

**Resource:** [Admin System Broadcast](../resources/Admin-System-Broadcast.md)
**Create a broadcast for system administration**
**Operation ID:** `post--admin-broadcasts`

Requires system/broadcast administrator permission. A successful creation returns no data payload.

## Request Body

Broadcast to create

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.Broadcast](../schemas/types-Broadcast/types-Broadcast.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

## Security

- **ApiKey**
