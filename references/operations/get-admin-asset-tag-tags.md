# GET /admin/asset/tag/tags

**Resource:** [Admin Asset Tag](../resources/Admin-Asset-Tag.md)
**Get /tags for asset/tag administration**
**Operation ID:** `get--admin-asset-tag-tags`

Requires asset/tag administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `category` | query | string | No | category name |
| `scope` | query | enum: model, dataset, code... | No | scope name |
| `built_in` | query | boolean | No | built_in |
| `search` | query | string | No | search on name and show_name fields |
| `per` | query | integer | No | Page size, default 50, max 100. When omitted and scope is set, all tags are returned without pagination |
| `page` | query | integer | No | Page number, default 1 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
