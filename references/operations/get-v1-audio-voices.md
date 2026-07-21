# GET /v1/audio/voices

**Resource:** [AIGateway](../resources/AIGateway.md)
**List available voices of a text-to-speech model**
**Operation ID:** `get--v1-audio-voices`

Proxies the OpenAI-compatible voices listing request to the backend TTS model

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `model` | query | string | Yes | Model ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 404 | Model not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
