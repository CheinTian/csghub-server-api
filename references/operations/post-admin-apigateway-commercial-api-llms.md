# POST /admin/apigateway/commercial_api/llms

**Resource:** [Admin Commercial API](../resources/Admin-Commercial-API.md)
**Create an LLM configuration for commercial API administration**
**Operation ID:** `post--admin-apigateway-commercial_api-llms`

Requires apigateway/commercial_api administrator permission.

## Request Body

LLM configuration

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateLLMConfigReq](../schemas/types-CreateLLMConfigReq/types-CreateLLMConfigReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
