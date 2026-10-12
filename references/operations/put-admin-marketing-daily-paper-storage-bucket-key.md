# PUT /admin/marketing/daily_paper/storage/{bucket}/{key}

**Resource:** [Admin Storage](../resources/Admin-Storage.md)
**Upload a marketing/daily_paper administrator object**
**Operation ID:** `put--admin-marketing-daily_paper-storage-{bucket}-{key}`

Requires marketing/daily_paper permission. Existing upload behavior, bucket, object key and public read URLs are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `bucket` | path | string | Yes | Bucket name |
| `key` | path | string | Yes | Object key |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `file` | string (binary) | Yes | File to upload |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
