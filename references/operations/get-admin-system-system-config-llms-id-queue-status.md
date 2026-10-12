# GET /admin/system/system_config/llms/{id}/queue_status

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**Get LLM upstream queue status for system configuration**
**Operation ID:** `get--admin-system-system_config-llms-{id}-queue_status`

Requires system/system_config administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | LLM configuration ID |

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
