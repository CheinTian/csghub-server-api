# POST /admin/system/system_config/llms

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**Create an LLM configuration for system configuration**
**Operation ID:** `post--admin-system-system_config-llms`

Requires system/system_config administrator permission.

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
