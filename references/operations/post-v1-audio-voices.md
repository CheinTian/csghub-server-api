# POST /v1/audio/voices

**Resource:** [AIGateway](../resources/AIGateway.md)
**Upload a voice sample for voice cloning**
**Operation ID:** `post--v1-audio-voices`

Proxies the multipart voice upload request to the backend TTS model. Only the deploy owner or platform admins are allowed.

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `model` | string | Yes | Model ID |
| `audio_sample` | string (binary) | Yes | Audio sample file |
| `consent` | string | Yes | Consent recording ID |
| `name` | string | Yes | Name for the new voice |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Permission denied |
| 404 | Model not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
