# POST /accounting/vouchers

**Resource:** [Accounting](../resources/Accounting.md)
**Create a new voucher**
**Operation ID:** `post--accounting-vouchers`

Create a new voucher for a user or organization with specified total amount, begin and end dates, and rules.

## Request Body

Voucher creation request parameters

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateVoucherReq](../schemas/types-CreateVoucherReq/types-CreateVoucherReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Voucher created successfully |
| 400 | Bad request format |
| 500 | Server error |

**Success Response Schema:**

[database.AccountVoucher](../schemas/database-AccountVoucher/database-AccountVoucher.md)

## Security

- **ApiKey**
