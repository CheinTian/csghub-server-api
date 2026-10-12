# GET /admin/broadcasts/{id}

**Resource:** [Admin System Broadcast](../resources/Admin-System-Broadcast.md)
**Get a broadcast for system administration**
**Operation ID:** `get--admin-broadcasts-{id}`

Requires system/broadcast administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Broadcast ID |

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
