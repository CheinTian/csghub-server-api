# POST /v1/messages

**Resource:** [AIGateway](../resources/AIGateway.md)
**Anthropic Messages API**
**Operation ID:** `post--v1-messages`

Create a message using the Anthropic Messages API format. Supports streaming and non-streaming responses, multi-turn conversations, tool use, vision, and thinking/reasoning. Requests are routed through the shared three-phase pipeline (Extract → Plan → Execute) with preflight tracing, LLM generation tracing, and LLM training log capture.

## Request Body

Anthropic Messages request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AnthropicMessagesRequest](../schemas/types-AnthropicMessagesRequest/types-AnthropicMessagesRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 402 | Payment Required |
| 404 | Not Found |
| 429 | Too Many Requests |
| 500 | Internal Server Error |
| 503 | Service Unavailable |

**Success Response Schema:**

[types.AnthropicMessagesResponse](../schemas/types-AnthropicMessagesResponse/types-AnthropicMessagesResponse.md)

