# types.LLMConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `availability_reason` | string | No |  |
| `created_at` | string | No |  |
| `enabled` | boolean | No |  |
| `id` | integer | No |  |
| `is_available` | boolean | No |  |
| `metadata` | object | No | tasks stored as: {"tasks": ["text-generation", "text-to-image"]} |
| `model_name` | string | No |  |
| `model_size_b` | number | No |  |
| `need_sensitive_check` | boolean | No |  |
| `repo` | [types.RepositoryLite](types-RepositoryLite.md) | No |  |
| `repo_id` | integer | No |  |
| `routing_policy` | [types.RoutingPolicy](types-RoutingPolicy.md) | No |  |
| `types` | integer[] | No | individual type flags derived from Type |
| `updated_at` | string | No |  |
| `upstreams` | types.UpstreamConfig[] | No |  |

