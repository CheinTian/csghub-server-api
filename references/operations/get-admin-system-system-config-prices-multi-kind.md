# GET /admin/system/system_config/prices/multi-kind

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**List prices for system configuration**
**Operation ID:** `get--admin-system-system_config-prices-multi-kind`

Requires system/system_config administrator permission.

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
