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
| `is_full_url` | boolean | No | IsFullURL marks the URL as a complete endpoint URL used as-is; when false
the URL is a base URL and the client protocol path is appended for the
supported API formats. |
| `llm_config_id` | integer | Yes |  |
| `metadata` | [types.UpstreamMetadata](types-UpstreamMetadata.md) | No |  |
| `model_name` | string | No |  |
| `provider` | string | No |  |
| `supported_endpoints` | object | No | SupportedEndpoints maps a declared protocol to an optional per-protocol
endpoint URL (empty value = the main URL serves that protocol). |
| `tags` | object | No |  |
| `url` | string | Yes |  |
| `weight` | integer | No |  |

