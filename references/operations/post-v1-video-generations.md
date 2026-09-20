# POST /v1/video/generations

**Resource:** [AIGateway](../resources/AIGateway.md)
**Create a video generation**
**Operation ID:** `post--v1-video-generations`

Creates an OpenAI-compatible text-to-video or image-to-video generation request.

## Request Body

Video generation request

**Required:** Yes

**Content Types:** `application/json`, `multipart/form-data`

**Schema:** [types.VideoGenerationRequest](../schemas/types-VideoGenerationRequest/types-VideoGenerationRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 404 | Model not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.VideoObject](../schemas/types-VideoObject/types-VideoObject.md)

