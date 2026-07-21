# types.CreateUpstreamReq

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auth_header` | string | No |  |
| `circuit_breaker_enabled` | boolean | No |  |
| `enabled` | boolean | No |  |
| `health_check_enabled` | boolean | No |  |
| `limit_policy` | [types.UsageLimitPolicy](types-UsageLimitPolicy.md) | No |  |
| `llm_config_id` | integer | Yes |  |
| `metadata` | object | No |  |
| `model_name` | string | No |  |
| `provider` | string | No |  |
| `tags` | object | No |  |
| `url` | string | Yes |  |
| `weight` | integer | No |  |

