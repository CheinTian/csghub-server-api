# DELETE /accounting/vouchers/{id}

**Resource:** [Accounting](../resources/Accounting.md)
**Delete a voucher**
**Operation ID:** `delete--accounting-vouchers-{id}`

Delete a voucher by voucher ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Voucher ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Voucher deleted successfully |
| 400 | Bad request format |
| 500 | Server error |

## Security

- **ApiKey**
