# POST /v1/ocr

**Resource:** [AIGateway](../resources/AIGateway.md)
**OCR**
**Operation ID:** `post--v1-ocr`

Extract text from an image or document with OCR

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `model` | string | Yes | Model ID |
| `file` | string (binary) | Yes | Image or PDF file |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 404 | Model not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.OCRResponse](../schemas/types-OCRResponse/types-OCRResponse.md)

