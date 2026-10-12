# PUT /admin/broadcasts/{id}

**Resource:** [Admin System Broadcast](../resources/Admin-System-Broadcast.md)
**Update a broadcast for system administration**
**Operation ID:** `put--admin-broadcasts-{id}`

Requires system/broadcast administrator permission. The path ID identifies the broadcast to update.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Broadcast ID |

## Request Body

Broadcast fields to update

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
