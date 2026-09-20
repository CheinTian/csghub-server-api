# POST /v1/audio/transcriptions

**Resource:** [AIGateway](../resources/AIGateway.md)
**Transcribe audio to text**
**Operation ID:** `post--v1-audio-transcriptions`

Sends an OpenAI-compatible multipart audio transcription request to the backend model

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `model` | string | Yes | Model ID |
| `file` | string (binary) | Yes | Audio file |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 404 | Model not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

