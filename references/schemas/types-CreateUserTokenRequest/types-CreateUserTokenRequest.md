# types.CreateUserTokenRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `application` | object | No | default to csghub |
| `expired_at` | string | No |  |
| `name` | string | No |  |
| `permission` | string | No | default to empty, means full permission |
| `quota` | number | No |  |
| `quota_type` | [types.AccountingQuotaType](types-AccountingQuotaType.md) | No |  |
| `quota_value_type` | [types.AccountingQuotaValueType](types-AccountingQuotaValueType.md) | No |  |

