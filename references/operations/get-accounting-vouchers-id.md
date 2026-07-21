# GET /accounting/vouchers/{id}

**Resource:** [Accounting](../resources/Accounting.md)
**Get a voucher by ID**
**Operation ID:** `get--accounting-vouchers-{id}`

Get voucher details by voucher ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Voucher ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Voucher retrieved successfully |
| 400 | Bad request format |
| 404 | Voucher not found |
| 500 | Server error |

**Success Response Schema:**

[database.AccountVoucher](../schemas/database-AccountVoucher/database-AccountVoucher.md)

## Security

- **ApiKey**
