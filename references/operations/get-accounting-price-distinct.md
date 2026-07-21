# GET /accounting/price/distinct

**Resource:** [Accounting](../resources/Accounting.md)
**Query distinct prices**
**Operation ID:** `get--accounting-price-distinct`

Query distinct prices by sku type, kind, resource id and status

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sku_type` | query | string | Yes | sku type |
| `sku_kind` | query | string | No | sku kind |
| `resource_id` | query | string | No | resource id |
| `sku_status` | query | string | No | sku status |
| `per` | query | integer | No | per |
| `page` | query | integer | No | per page |
| `current_user` | query | string | Yes | current_user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
