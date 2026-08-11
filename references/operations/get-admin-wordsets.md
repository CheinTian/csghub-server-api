# GET /admin/wordsets

**Resource:** [Moderation](../resources/Moderation.md)
**List sensitive word sets**
**Operation ID:** `get--admin-wordsets`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | Search string |
| `per` | query | integer | No | Page size, default 50, max 100 |
| `page` | query | integer | No | Page number, default 1 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

