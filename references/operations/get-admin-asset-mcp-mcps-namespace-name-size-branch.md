# GET /admin/asset/mcp/mcps/{namespace}/{name}/size/{branch}

**Resource:** [Admin Asset MCP](../resources/Admin-Asset-MCP.md)
**Size mcp resources for asset administration**
**Operation ID:** `get--admin-asset-mcp-mcps-{namespace}-{name}-size-{branch}`

Requires asset/mcp administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | repo owner name |
| `name` | path | string | Yes | repo name |
| `branch` | path | string | Yes | branch name |

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
