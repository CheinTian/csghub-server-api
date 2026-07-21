# POST /v1/audio/speech/batch

**Resource:** [AIGateway](../resources/AIGateway.md)
**Generate speech for multiple texts in a single request**
**Operation ID:** `post--v1-audio-speech-batch`

Sends an OpenAI-compatible batch text-to-speech request to the backend model and returns base64-encoded audio results

## Request Body

Batch speech generation request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [handler.BatchSpeechRequest](../schemas/handler-BatchSpeechRequest/handler-BatchSpeechRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request or sensitive input |
| 404 | Model not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
