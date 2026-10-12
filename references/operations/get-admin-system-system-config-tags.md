# GET /admin/system/system_config/tags

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**List tags for system configuration**
**Operation ID:** `get--admin-system-system_config-tags`

Requires system/system_config administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scope` | query | string | No | Repository scope |
| `built_in` | query | boolean | No | Built-in tags only |
| `category` | query | string | No | Tag category |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
