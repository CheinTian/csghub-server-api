# types.CreateUpstreamReq

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auth_header` | string | No |  |
| `capacity_policy` | [types.CapacityPolicy](types-CapacityPolicy.md) | No |  |
| `circuit_breaker_enabled` | boolean | No |  |
| `enabled` | boolean | No |  |
| `health_check_enabled` | boolean | No |  |
| `llm_config_id` | integer | Yes |  |
| `metadata` | [types.UpstreamMetadata](types-UpstreamMetadata.md) | No |  |
| `model_name` | string | No |  |
| `provider` | string | No |  |
| `tags` | object | No |  |
| `url` | string | Yes |  |
| `weight` | integer | No |  |

