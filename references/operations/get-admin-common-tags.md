# GET /admin/common/tags

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Get tag choices for the administrator navigation bar**
**Operation ID:** `get--admin-common-tags`

Requires any active administrator role. Industry choices use scope=model and category=industry.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `category` | query | string | No | Category name |
| `scope` | query | enum: model, dataset, code... | No | Scope name |
| `built_in` | query | boolean | No | Filter built-in tags |
| `search` | query | string | No | Search name and show_name |
| `per` | query | integer | No | Page size, default 50, max 100. When omitted with scope set, all matching tags are returned |
| `page` | query | integer | No | Page number |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

## Security

- **ApiKey**
