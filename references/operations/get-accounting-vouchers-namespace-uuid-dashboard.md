# GET /accounting/vouchers/namespace/{uuid}/dashboard

**Resource:** [Accounting](../resources/Accounting.md)
**Get voucher dashboard data**
**Operation ID:** `get--accounting-vouchers-namespace-{uuid}-dashboard`

Get voucher dashboard data for a given namespace UUID, including total amount and count grouped by voucher status.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | User or Org UUID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Voucher dashboard data retrieved successfully |
| 400 | Bad request format |
| 403 | Forbidden |
| 500 | Server error |

**Success Response Schema:**

[types.VoucherDashboardResp](../schemas/types-VoucherDashboardResp/types-VoucherDashboardResp.md)

## Security

- **ApiKey**
