# database.AccountVoucher

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `begin_date` | string | No |  |
| `created_at` | string | No |  |
| `end_date` | string | No |  |
| `id` | integer | No |  |
| `issue_name` | string | No |  |
| `issue_uuid` | string | No |  |
| `notes` | string | No |  |
| `rules` | types.VoucherRules[] | No |  |
| `status` | [types.VoucherStatus](types-VoucherStatus.md) | No |  |
| `target_name` | string | No |  |
| `target_type` | object | No | user or org |
| `target_uuid` | string | No |  |
| `total` | number | No |  |
| `updated_at` | string | No |  |
| `used` | number | No |  |
| `voucher_no` | string | No |  |

