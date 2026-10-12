# types.AIGatewayMetricEventLog

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `api_key_masked` | string | No |  |
| `cache_creation_tokens` | integer | No |  |
| `cached_tokens` | integer | No |  |
| `completion_tokens` | integer | No |  |
| `created_at` | string | No |  |
| `error_message` | string | No |  |
| `error_type` | string | No |  |
| `is_stream` | boolean | No |  |
| `latency_ms` | integer | No |  |
| `llm_config_id` | integer | No |  |
| `model` | string | No |  |
| `prompt_tokens` | integer | No |  |
| `provider` | string | No |  |
| `queue_wait_ms` | integer | No |  |
| `request_id` | string | No |  |
| `start_time` | string | No | StartTime is the full-precision request start time, pre-formatted in
the global product timezone ("2006-01-02 15:04:05"); empty for rows
written before the diagnostics columns existed, so the frontend can
fall back to CreatedAt. |
| `status_code` | integer | No |  |
| `total_tokens` | integer | No |  |
| `ttft_ms` | integer | No |  |
| `upstream_id` | integer | No |  |
| `username` | string | No |  |

