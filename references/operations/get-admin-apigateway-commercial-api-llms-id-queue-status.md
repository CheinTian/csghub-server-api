# GET /admin/apigateway/commercial_api/llms/{id}/queue_status

**Resource:** [Admin Commercial API](../resources/Admin-Commercial-API.md)
**Get LLM upstream queue status for commercial API administration**
**Operation ID:** `get--admin-apigateway-commercial_api-llms-{id}-queue_status`

Requires apigateway/commercial_api administrator permission.

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
