# types.CreateLLMConfigReq

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |
| `metadata` | object | No | tasks stored as: {"tasks": ["text-generation", "text-to-image"]} |
| `model_name` | string | Yes |  |
| `model_size_b` | number | No |  |
| `need_sensitive_check` | boolean | No |  |
| `repo_id` | integer | No |  |
| `routing_policy` | [types.RoutingPolicy](types-RoutingPolicy.md) | No |  |
| `types` | integer[] | Yes | individual type flags, combined into a bitmask on create |
| `upstreams` | types.UpstreamConfig[] | No |  |

