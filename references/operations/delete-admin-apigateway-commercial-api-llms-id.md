# DELETE /admin/apigateway/commercial_api/llms/{id}

**Resource:** [Admin Commercial API](../resources/Admin-Commercial-API.md)
**Delete an LLM configuration for commercial API administration**
**Operation ID:** `delete--admin-apigateway-commercial_api-llms-{id}`

Requires apigateway/commercial_api administrator permission.

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

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
