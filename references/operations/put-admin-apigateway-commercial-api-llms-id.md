# PUT /admin/apigateway/commercial_api/llms/{id}

**Resource:** [Admin Commercial API](../resources/Admin-Commercial-API.md)
**Update an LLM configuration for commercial API administration**
**Operation ID:** `put--admin-apigateway-commercial_api-llms-{id}`

Requires apigateway/commercial_api administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | LLM configuration ID |

## Request Body

LLM configuration

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateLLMConfigReq](../schemas/types-UpdateLLMConfigReq/types-UpdateLLMConfigReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
