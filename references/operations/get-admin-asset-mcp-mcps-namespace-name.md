# GET /admin/asset/mcp/mcps/{namespace}/{name}

**Resource:** [Admin Asset MCP](../resources/Admin-Asset-MCP.md)
**Show mcp resources for asset administration**
**Operation ID:** `get--admin-asset-mcp-mcps-{namespace}-{name}`

Requires asset/mcp administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `need_op_weight` | query | boolean | No | need op weight |
| `need_multi_sync` | query | boolean | No | need multi sync |

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
