# POST /accounting/price/batch

**Resource:** [Accounting](../resources/Accounting.md)
**Batch create sku prices**
**Operation ID:** `post--accounting-price-batch`

Batch create sku prices, will disable existing enabled prices with same sku_type+sku_kind+resource_id combination

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `current_user` | query | string | Yes | current_user |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AcctPriceBatchCreateReq](../schemas/types-AcctPriceBatchCreateReq/types-AcctPriceBatchCreateReq.md)

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
