# GET /config/prompt_prefixes/{id}

**Resource:** [LLMService](../resources/LLMService.md)
**Get detail of prompt config by id**
**Operation ID:** `get--config-prompt_prefixes-{id}`

Retrieve a prompt prefix by ID. Requires system/system_config administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | PromptPrefix.ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

