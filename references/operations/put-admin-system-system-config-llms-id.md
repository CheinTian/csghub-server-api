# PUT /admin/system/system_config/llms/{id}

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**Update an LLM configuration for system configuration**
**Operation ID:** `put--admin-system-system_config-llms-{id}`

Requires system/system_config administrator permission.

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
