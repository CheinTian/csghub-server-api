# POST /v1/chat/completions

**Resource:** [AIGateway](../resources/AIGateway.md)
**Create chat completion**
**Operation ID:** `post--v1-chat-completions`

Sends an OpenAI-compatible chat completion request to the backend model and returns the response. Streams Server-Sent Events when `stream: true`.

## Request Body

Chat completion request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.ChatCompletionRequest](../schemas/types-ChatCompletionRequest/types-ChatCompletionRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Server-Sent Events stream when stream=true |
| 400 | Bad request |
| 402 | Insufficient balance |
| 404 | Model not found |
| 429 | Usage limit exceeded |
| 500 | Internal server error |

## Security

- **ApiKey**
