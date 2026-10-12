# POST /admin/system/system_config/upstreams/{id}/test

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**Test an upstream for system configuration**
**Operation ID:** `post--admin-system-system_config-upstreams-{id}-test`

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

## Security

- **ApiKey**
