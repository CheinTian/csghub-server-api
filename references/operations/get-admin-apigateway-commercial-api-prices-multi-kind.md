# GET /admin/apigateway/commercial_api/prices/multi-kind

**Resource:** [Admin Commercial API](../resources/Admin-Commercial-API.md)
**List prices for commercial API administration**
**Operation ID:** `get--admin-apigateway-commercial_api-prices-multi-kind`

Requires apigateway/commercial_api administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sku_type` | query | string | No | SKU type |
| `sku_kind` | query | string | No | JSON array of SKU kinds |
| `resource_id` | query | string | No | Resource ID |

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
