# PUT /accounting/vouchers/{id}/revoke

**Resource:** [Accounting](../resources/Accounting.md)
**Revoke a voucher**
**Operation ID:** `put--accounting-vouchers-{id}-revoke`

Revoke a pending voucher by voucher ID. Only vouchers with pending status can be revoked.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Voucher ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Voucher revoked successfully |
| 400 | Bad request format |
| 404 | Voucher not found |
| 500 | Server error |

**Success Response Schema:**

[database.AccountVoucher](../schemas/database-AccountVoucher/database-AccountVoucher.md)

## Security

- **ApiKey**
