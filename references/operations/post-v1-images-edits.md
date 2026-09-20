# POST /v1/images/edits

**Resource:** [AIGateway](../resources/AIGateway.md)
**Edit image from prompt and input image**
**Operation ID:** `post--v1-images-edits`

Edits images with an OpenAI-compatible multipart/form-data request

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `model` | string | Yes | Model ID |
| `prompt` | string | Yes | Edit prompt |
| `image` | string (binary) | Yes | Input image |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request or sensitive input |
| 404 | Model not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.ImageGenerationResponse](../schemas/types-ImageGenerationResponse/types-ImageGenerationResponse.md)

