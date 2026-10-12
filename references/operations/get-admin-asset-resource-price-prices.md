# GET /admin/asset/resource_price/prices

**Resource:** [Admin asset/resource_price](../resources/Admin-asset-resource-price.md)
**List prices for asset/resource_price administration**
**Operation ID:** `get--admin-asset-resource_price-prices`

Requires asset/resource_price administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sku_type` | query | enum: 1, 2 | Yes | sku_type |
| `sku_kind` | query | string | Yes | sku_kind |
| `sku_status` | query | enum: 1, 9 | No | sku_status |
| `resource_id` | query | string | Yes | resource_id |
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
