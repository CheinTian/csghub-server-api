# POST /v1/responses

**Resource:** [AIGateway](../resources/AIGateway.md)
**Create a model response**
**Operation ID:** `post--v1-responses`

Sends an OpenAI-compatible Responses API request to the backend model and returns the response. Streams Server-Sent Events when `stream: true`.

## Request Body

Responses request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.ResponsesRequest](../schemas/types-ResponsesRequest/types-ResponsesRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Server-Sent Events stream when stream=true |
| 400 | Bad request or unsupported feature |
| 402 | Insufficient balance or usage limit exceeded |
| 404 | Model not found |
| 500 | Internal server error |
| 502 | Upstream returned an invalid response |

## Security

- **ApiKey**
