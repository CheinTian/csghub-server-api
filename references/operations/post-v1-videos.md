# POST /v1/videos

**Resource:** [AIGateway](../resources/AIGateway.md)
**Create a video generation**
**Operation ID:** `post--v1-videos`

Creates an OpenAI-compatible text-to-video or image-to-video generation request. Image input can be supplied by JSON input_reference or multipart input_reference.

## Request Body

**Content Types:** `application/json`, `multipart/form-data`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `model` | string | No | Model ID for multipart requests |
| `prompt` | string | No | Video prompt for multipart requests |
| `size` | string | No | Video size for multipart requests |
| `seconds` | integer (int32) | No | Video duration in seconds for multipart requests |
| `input_reference` | string (binary) | No | Image input reference for multipart image-to-video requests |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 404 | Model not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.VideoObject](../schemas/types-VideoObject/types-VideoObject.md)

## Security

- **ApiKey**
