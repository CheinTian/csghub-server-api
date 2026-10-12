# POST /admin/asset/mcp/recom/opweight

**Resource:** [Admin Asset MCP](../resources/Admin-Asset-MCP.md)
**Update recommendation weight for MCP administration**
**Operation ID:** `post--admin-asset-mcp-recom-opweight`

Requires asset/mcp permission and a target repository whose stored type is mcpserver; a type mismatch returns 403 without updating weights.

## Request Body

Repository ID and recommendation weight

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [handler.SetOpWeight.SetOpWeightReq](../schemas/handler-SetOpWeight-SetOpWeightReq/handler-SetOpWeight-SetOpWeightReq.md)

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
