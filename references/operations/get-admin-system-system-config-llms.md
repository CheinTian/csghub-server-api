# GET /admin/system/system_config/llms

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**List LLM configurations for system configuration**
**Operation ID:** `get--admin-system-system_config-llms`

Requires system/system_config administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |
| `keyword` | query | string | No | Model name search |
| `types` | query | integer[] | No | LLM type flags |
| `enabled` | query | boolean | No | Enabled state |
| `sort_by` | query | enum: model_size_b, updated_at | No | Sort field |
| `sort_order` | query | enum: ASC, DESC | No | Sort order |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
