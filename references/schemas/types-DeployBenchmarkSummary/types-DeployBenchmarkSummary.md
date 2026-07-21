# types.DeployBenchmarkSummary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avg_latency_ms` | number | No |  |
| `completion_tokens` | integer | No |  |
| `failed_requests` | integer | No |  |
| `p95_latency_ms` | number | No |  |
| `p99_latency_ms` | number | No |  |
| `prompt_tokens` | integer | No |  |
| `rps` | number | No | Requests Per Second |
| `success_rate` | number | No |  |
| `success_requests` | integer | No |  |
| `total_requests` | integer | No |  |
| `total_tokens` | integer | No |  |
| `tpm` | number | No | Tokens Per Minute |
| `ttft_available` | boolean | No | true if TTFT was measured from streaming response |
| `ttft_ms` | number | No | Time To First Token, only meaningful for streaming requests |

