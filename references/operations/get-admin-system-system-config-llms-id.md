# GET /admin/system/system_config/llms/{id}

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**Get an LLM configuration for system configuration**
**Operation ID:** `get--admin-system-system_config-llms-{id}`

Requires system/system_config administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | LLM configuration ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
