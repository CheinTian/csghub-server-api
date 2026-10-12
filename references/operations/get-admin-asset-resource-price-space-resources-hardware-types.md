# GET /admin/asset/resource_price/space_resources/hardware_types

**Resource:** [Admin Asset Resource Price](../resources/Admin-Asset-Resource-Price.md)
**Read /space_resources/hardware_types for asset/resource_price administration**
**Operation ID:** `get--admin-asset-resource_price-space_resources-hardware_types`

Requires asset/resource_price administrator permission; original query parameters are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cluster_id` | query | string | No | Cluster ID |

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
