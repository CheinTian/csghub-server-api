# types.DeployBenchmarkConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `concurrency` | integer | No |  |
| `duration_seconds` | integer | No |  |
| `enable_stream` | boolean | No |  |
| `max_concurrency` | integer | No |  |
| `p95_latency_ms_max` | number | No | max allowed p95 latency in milliseconds, 0 means no limit |
| `sample_message` | string | No |  |
| `success_rate_min` | number | No |  |
| `timeout_seconds` | integer | No |  |
| `tpm_target` | number | No |  |
| `warmup_requests` | integer | No |  |

