# POST /config/llms

**Resource:** [LLMService](../resources/LLMService.md)
**Create LLM Config**
**Operation ID:** `post--config-llms`

Create LLM Config according to "model_name", "upstreams", "types", "enabled". Types is an array of type flags (1, 2, 4, 8, 16) that are combined into an internal bitmask.

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateLLMConfigReq](../schemas/types-CreateLLMConfigReq/types-CreateLLMConfigReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

