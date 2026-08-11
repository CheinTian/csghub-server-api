# GET /tags

**Resource:** [Tag](../resources/Tag.md)
**Get all tags**
**Operation ID:** `get--tags`

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
| 200 | tags |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
