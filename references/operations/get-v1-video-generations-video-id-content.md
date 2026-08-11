# GET /v1/video/generations/{video_id}/content

**Resource:** [AIGateway](../resources/AIGateway.md)
**Download generated video content**
**Operation ID:** `get--v1-video-generations-{video_id}-content`

Streams generated video bytes for an OpenAI-compatible video generation by gateway video ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `video_id` | path | string | Yes | Gateway video ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Generated video content |
| 400 | Bad request |
| 404 | Video not found |
| 500 | Internal server error |

## Security

- **ApiKey**
