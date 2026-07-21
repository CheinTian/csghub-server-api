# PUT /accounting/vouchers/{id}

**Resource:** [Accounting](../resources/Accounting.md)
**Update a voucher**
**Operation ID:** `put--accounting-vouchers-{id}`

Update voucher details such as total amount, begin/end dates, rules, or notes by voucher ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Voucher ID |

## Request Body

Voucher update request parameters

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateVoucherReq](../schemas/types-UpdateVoucherReq/types-UpdateVoucherReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Voucher updated successfully |
| 400 | Bad request format |
| 404 | Voucher not found |
| 500 | Server error |

**Success Response Schema:**

[database.AccountVoucher](../schemas/database-AccountVoucher/database-AccountVoucher.md)

## Security

- **ApiKey**
