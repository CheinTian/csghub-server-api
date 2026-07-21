# types.CreateAPIKeyRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expired_at` | string | No |  |
| `name` | string | Yes |  |
| `quota` | number | No |  |
| `quota_type` | [types.AccountingQuotaType](types-AccountingQuotaType.md) | Yes |  |
| `quota_value_type` | [types.AccountingQuotaValueType](types-AccountingQuotaValueType.md) | Yes |  |

