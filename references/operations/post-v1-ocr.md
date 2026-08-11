# POST /v1/ocr

**Resource:** [AIGateway](../resources/AIGateway.md)
**Extract text from an image with OCR**
**Operation ID:** `post--v1-ocr`

Sends a multipart OCR request to a PaddleOCR-capable backend model and returns normalized text, pages and lines. PDF input is not supported yet; page_ranges is accepted for API stability but not forwarded upstream.

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `model` | string | Yes | Model ID |
| `file` | string (binary) | Yes | Image file (png, jpeg, webp, bmp, tiff) |
| `page_ranges` | string | No | Page range for multi-page input, e.g. 1,3-5 (reserved) |
| `use_doc_orientation_classify` | boolean | No | Enable document orientation classification |
| `use_doc_unwarping` | boolean | No | Enable document unwarping |
| `use_textline_orientation` | boolean | No | Enable text line orientation classification |
| `return_image` | boolean | No | Ask upstream to visualize results (images surface only in raw_result) |
| `raw_response` | boolean | No | Include the raw upstream OCR result in the response |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 404 | Model not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.OCRResponse](../schemas/types-OCRResponse/types-OCRResponse.md)

## Security

- **ApiKey**
