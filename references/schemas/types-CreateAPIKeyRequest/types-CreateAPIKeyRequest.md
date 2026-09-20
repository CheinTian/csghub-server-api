# types.CreateAPIKeyRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expired_at` | string | No |  |
| `name` | string | Yes |  |
| `quotas` | types.UpdateAPIKeyQuotaItem[] | Yes | Quotas supports submitting multiple quota records in one request. |

