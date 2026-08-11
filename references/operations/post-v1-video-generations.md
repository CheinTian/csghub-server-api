# POST /v1/video/generations

**Resource:** [AIGateway](../resources/AIGateway.md)
**Create a video generation**
**Operation ID:** `post--v1-video-generations`

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
| `audio` | string (binary) | No | Audio reference; repeat once per speaker (maximum two) |
| `audio_type` | string | No | Multi-speaker audio mode: para or add |
| `num_segments` | integer (int32) | No | Number of generated continuation segments |
| `ref_img_index` | integer (int32) | No | Reference image frame index for continuation |
| `mask_frame_range` | integer (int32) | No | Reference mask frame range for continuation |
| `bbox` | string | No | Speaker bounding boxes as JSON using [ymin,xmin,ymax,xmax] |

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
