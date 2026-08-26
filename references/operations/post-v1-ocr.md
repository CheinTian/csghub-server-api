# POST /v1/ocr

**Resource:** [AIGateway](../resources/AIGateway.md)
**Extract text from an image or document with OCR**
**Operation ID:** `post--v1-ocr`

Sends a multipart OCR request to a PaddleOCR-capable backend model and returns normalized text and pages. PDF input requires the paddleocr-vl runtime.

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `model` | string | Yes | Model ID |
| `file` | string (binary) | Yes | Image or PDF file (PDF requires paddleocr-vl) |
| `page_ranges` | string | No | Reserved; non-empty values are rejected |
| `use_doc_orientation_classify` | boolean | No | Enable document orientation classification |
| `use_doc_unwarping` | boolean | No | Enable document unwarping |
| `use_textline_orientation` | boolean | No | Enable text line orientation classification |
| `return_image` | boolean | No | Return embedded document images in pages[].images (base64) |
| `raw_response` | boolean | No | Include the raw upstream OCR result in the response (does not request embedded markdown images; pass return_image=true for those) |

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
