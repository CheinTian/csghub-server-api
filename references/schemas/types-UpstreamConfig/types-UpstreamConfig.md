# types.UpstreamConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auth_header` | string | No | AuthHeader is endpoint-specific auth header value.
It supports either a plain "Bearer xxx" string or JSON object string like {"Authorization":"Bearer xxx"}. |
| `availability_status` | string | No | AvailabilityStatus is a readable aggregate status: available/degraded/unavailable/disabled. |
| `circuit_breaker_enabled` | boolean | No |  |
| `circuit_state` | string | No | CircuitState is populated for admin views from the circuit state table. |
| `enabled` | boolean | No |  |
| `health_check_enabled` | boolean | No |  |
| `health_state` | string | No | HealthState is populated for admin views from the health state table. |
| `id` | integer | No |  |
| `is_available` | boolean | No | IsAvailable is the computed overall availability for this upstream. |
| `limit_policy` | object | No | LimitPolicy controls usage-based quota for this specific endpoint. |
| `metadata` | object | No |  |
| `model_name` | string | No | ModelName overrides the upstream request model ID when this upstream uses |
| `provider` | string | No | Provider identifies upstream provider for this specific endpoint. |
| `tags` | object | No |  |
| `url` | string | No |  |
| `weight` | integer | No |  |

