# GET /config/prompt_prefixes

**Resource:** [LLMService](../resources/LLMService.md)
**Get Prompt Config**
**Operation ID:** `get--config-prompt_prefixes`

Get prompt prefixes with optional filters. Requires system/system_config administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | which batch of results to retrieve |
| `per` | query | integer | No | the batch size to return in a single response |
| `keyword` | query | string | No | search in prompt.zh |
| `kind` | query | string | No | search in prompt.kind |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

