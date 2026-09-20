# types.UpstreamConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auth_header` | string | No | AuthHeader is endpoint-specific auth header value.
It supports either a plain "Bearer xxx" string or JSON object string like {"Authorization":"Bearer xxx"}. |
| `availability_status` | string | No | AvailabilityStatus is a readable aggregate status: available/degraded/unavailable/disabled. |
| `capacity_policy` | object | No | CapacityPolicy controls per-upstream capacity limits (concurrency, RPM, TPM, queue). |
| `circuit_breaker_enabled` | boolean | No |  |
| `circuit_state` | string | No | CircuitState is populated for admin views from the circuit state table. |
| `enabled` | boolean | No |  |
| `health_check_enabled` | boolean | No |  |
| `health_state` | string | No | HealthState is populated for admin views from the health state table. |
| `id` | integer | No |  |
| `is_available` | boolean | No | IsAvailable is the computed overall availability for this upstream. |
| `metadata` | [types.UpstreamMetadata](types-UpstreamMetadata.md) | No |  |
| `model_name` | string | No | ModelName overrides the upstream request model ID when this upstream uses |
| `provider` | string | No | Provider identifies upstream provider for this specific endpoint. |
| `source` | [types.UpstreamSource](types-UpstreamSource.md) | No |  |
| `source_id` | integer | No |  |
| `tags` | object | No |  |
| `url` | string | No |  |
| `weight` | integer | No |  |

