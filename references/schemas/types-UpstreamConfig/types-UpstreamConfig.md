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
| `consecutive_failures` | integer | No | ConsecutiveFailures counts consecutive failed health checks. |
| `enabled` | boolean | No |  |
| `health_check_enabled` | boolean | No |  |
| `health_state` | string | No | HealthState is populated for admin views from the health state table. |
| `id` | integer | No |  |
| `is_available` | boolean | No | IsAvailable is the computed overall availability for this upstream. |
| `is_full_url` | boolean | No | IsFullURL marks the URL as a complete endpoint URL used as-is (no path
appended). When false the URL is a base URL and the client protocol
path is appended for natively supported API formats. |
| `last_check_at` | string | No | LastCheckAt is the time of the latest health check, populated for admin views. |
| `last_error` | string | No | LastError is the detail of the latest failed health check (reason/HTTP code/response),
populated for admin views from the health state table. |
| `latency_ms` | integer | No | LatencyMs is the latency of the latest health check in milliseconds. |
| `metadata` | [types.UpstreamMetadata](types-UpstreamMetadata.md) | No |  |
| `model_name` | string | No | ModelName overrides the upstream request model ID when this upstream uses |
| `provider` | string | No | Provider identifies upstream provider for this specific endpoint. |
| `source` | [types.UpstreamSource](types-UpstreamSource.md) | No |  |
| `source_id` | integer | No |  |
| `supported_endpoints` | object | No | SupportedEndpoints maps a protocol (chat / responses / messages) to an
optional per-protocol endpoint URL. An empty value means the protocol
is served by the main URL field (full URL as-is, or base URL with the
protocol path appended). A missing key means the protocol is not
declared; routing falls back to URL inference and legacy adapters. |
| `tags` | object | No |  |
| `url` | string | No |  |
| `weight` | integer | No |  |

