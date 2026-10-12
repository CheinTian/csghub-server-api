# GET /admin/asset/mcp/mcps/tools

**Resource:** [Admin Asset Mcp](../resources/Admin-Asset-Mcp.md)
**Get /mcps/tools for asset/mcp administration**
**Operation ID:** `get--admin-asset-mcp-mcps-tools`

Requires asset/mcp administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | search text |
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
