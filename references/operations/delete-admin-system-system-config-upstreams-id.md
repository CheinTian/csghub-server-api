# DELETE /admin/system/system_config/upstreams/{id}

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**Delete an upstream for system configuration**
**Operation ID:** `delete--admin-system-system_config-upstreams-{id}`

Requires system/system_config administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Upstream ID |

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
