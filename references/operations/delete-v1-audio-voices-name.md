# DELETE /v1/audio/voices/{name}

**Resource:** [AIGateway](../resources/AIGateway.md)
**Delete an uploaded voice sample**
**Operation ID:** `delete--v1-audio-voices-{name}`

Proxies the voice deletion request to the backend TTS model. Only the deploy owner or platform admins are allowed.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | path | string | Yes | Name of the voice to delete |
| `model` | query | string | Yes | Model ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Permission denied |
| 404 | Model or voice not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
