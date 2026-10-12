# POST /config/prompt_prefixes

**Resource:** [LLMService](../resources/LLMService.md)
**Create Prompt Config**
**Operation ID:** `post--config-prompt_prefixes`

Create a prompt prefix. Requires system/system_config administrator permission.

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreatePromptPrefixReq](../schemas/types-CreatePromptPrefixReq/types-CreatePromptPrefixReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

