# GET /admin/apigateway/public_inference/prices/multi-kind

**Resource:** [Admin apigateway/public_inference](../resources/Admin-apigateway-public-inference.md)
**List prices/multi-kind for apigateway/public_inference administration**
**Operation ID:** `get--admin-apigateway-public_inference-prices-multi-kind`

Requires apigateway/public_inference administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sku_type` | query | enum: 1, 2 | Yes | sku_type |
| `sku_kind` | query | string | Yes | JSON array of SKU kinds, e.g. [4,5,7] |
| `resource_id` | query | string | No | resource_id |

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
