# PUT /admin/asset/mcp/mcps/{namespace}/{name}

**Resource:** [Admin Asset MCP](../resources/Admin-Asset-MCP.md)
**Update mcp resources for asset administration**
**Operation ID:** `put--admin-asset-mcp-mcps-{namespace}-{name}`

Requires asset/mcp administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateMCPServerReq](../schemas/types-UpdateMCPServerReq/types-UpdateMCPServerReq.md)

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
