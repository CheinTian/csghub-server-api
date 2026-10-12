# GET /accounting/internal/vouchers/namespace/{uuid}/dashboard

**Resource:** [Accounting internal](../resources/Accounting-internal.md)
**Get voucher billing facts for internal services**
**Operation ID:** `get--accounting-internal-vouchers-namespace-{uuid}-dashboard`

Requires the system service API key; no additional user role is required.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | Billing namespace UUID |
| `cluster_id` | query | string | No | Cluster ID |
| `xpu_model` | query | string | No | Accelerator model |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 500 | Internal Server Error |

## Security

- **ApiKey**
