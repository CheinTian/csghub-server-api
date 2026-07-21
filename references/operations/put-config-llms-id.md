# PUT /config/llms/{id}

**Resource:** [LLMService](../resources/LLMService.md)
**Update LLM Config**
**Operation ID:** `put--config-llms-{id}`

Update existing LLM configuration by ID. If input ModelName, Upstreams, Types, Enabled are not null, update in database. Types is an array of type flags (1, 2, 4, 8, 16). Return the updated LLM configuration. If the provided ID does not exist, it returns an error.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | id |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateLLMConfigReq](../schemas/types-UpdateLLMConfigReq/types-UpdateLLMConfigReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

