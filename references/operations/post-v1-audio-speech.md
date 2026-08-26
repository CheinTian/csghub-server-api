# POST /v1/audio/speech

**Resource:** [AIGateway](../resources/AIGateway.md)
**Generate speech from text**
**Operation ID:** `post--v1-audio-speech`

Sends an OpenAI-compatible text-to-speech request to the backend model and returns audio

## Request Body

Speech generation request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.SpeechRequest](../schemas/types-SpeechRequest/types-SpeechRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Audio data |
| 400 | Bad request or sensitive input |
| 404 | Model not found |
| 500 | Internal server error |

## Security

- **ApiKey**
