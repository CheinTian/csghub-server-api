# GET /admin/apigateway/commercial_api/llms

**Resource:** [Admin Commercial API](../resources/Admin-Commercial-API.md)
**List LLM configurations for commercial API administration**
**Operation ID:** `get--admin-apigateway-commercial_api-llms`

Requires apigateway/commercial_api administrator permission.

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
