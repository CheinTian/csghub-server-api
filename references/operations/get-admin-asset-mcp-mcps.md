# GET /admin/asset/mcp/mcps

**Resource:** [Admin Asset MCP](../resources/Admin-Asset-MCP.md)
**List mcp resources for asset administration**
**Operation ID:** `get--admin-asset-mcp-mcps`

Requires asset/mcp administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tag_category` | query | string | No | filter by tag category |
| `tag_name` | query | string | No | filter by tag name |
| `tag_group` | query | string | No | filter by tag group |
| `need_op_weight` | query | boolean | No | need op weight |
| `search` | query | string | No | search text |
| `sort` | query | string | No | sort by |
| `per` | query | integer | No | per |
| `page` | query | integer | No | per page |

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
