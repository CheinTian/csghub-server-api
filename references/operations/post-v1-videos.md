# POST /v1/videos

**Resource:** [AIGateway](../resources/AIGateway.md)
**Create a video generation (deprecated)**
**Operation ID:** `post--v1-videos`
⚠️ **Deprecated**

Deprecated: use POST /v1/video/generations instead.

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

## Security

- **ApiKey**
