# GET /accounting/vouchers/namespace/{uuid}/bill

**Resource:** [Accounting](../resources/Accounting.md)
**Get voucher bill grouped data**
**Operation ID:** `get--accounting-vouchers-namespace-{uuid}-bill`

Get voucher bill data grouped by scene and customer ID for a given namespace UUID, with required voucher number and date range, and optional scene and instance name filters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | User or Org UUID |
| `voucher_no` | query | string | Yes | Voucher number |
| `start_date` | query | string | Yes | Start date |
| `end_date` | query | string | Yes | End date |
| `scene` | query | integer | No | Scene type filter |
| `instance_name` | query | string | No | Instance name filter |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Voucher bill data retrieved successfully |
| 400 | Bad request format |
| 403 | Forbidden |
| 500 | Server error |

**Success Response Schema:**

Array of [database.VoucherBillGroupedResult](../schemas/database-VoucherBillGroupedResult/database-VoucherBillGroupedResult.md)

## Security

- **ApiKey**
