# GET /v1/videos/{video_id}

**Resource:** [AIGateway](../resources/AIGateway.md)
**Get a video generation (deprecated)**
**Operation ID:** `get--v1-videos-{video_id}`
⚠️ **Deprecated**

Deprecated: use GET /v1/video/generations/{video_id} instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `video_id` | path | string | Yes | Gateway video ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 404 | Video not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.VideoObject](../schemas/types-VideoObject/types-VideoObject.md)

## Security

- **ApiKey**
