# GET /admin/asset/resource_price/cluster

**Resource:** [Admin Asset Resource Price](../resources/Admin-Asset-Resource-Price.md)
**Read /cluster for asset/resource_price administration**
**Operation ID:** `get--admin-asset-resource_price-cluster`

Requires asset/resource_price administrator permission; original query parameters are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scope` | query | enum: all | No | Scope of cluster |

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
