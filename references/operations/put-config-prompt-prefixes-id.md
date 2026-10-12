# PUT /config/prompt_prefixes/{id}

**Resource:** [LLMService](../resources/LLMService.md)
**Update Prompt Config**
**Operation ID:** `put--config-prompt_prefixes-{id}`

Update an existing prompt prefix by ID. Requires system/system_config administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | prompt_prefix.id |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdatePromptPrefixReq](../schemas/types-UpdatePromptPrefixReq/types-UpdatePromptPrefixReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

