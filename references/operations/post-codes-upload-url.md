# POST /codes/upload_url

**Resource:** [Code](../resources/Code.md)
**Get code package upload URL**
**Operation ID:** `post--codes-upload_url`

Get a presigned URL and form data for uploading code package

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `current_user` | query | string | No | current user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
