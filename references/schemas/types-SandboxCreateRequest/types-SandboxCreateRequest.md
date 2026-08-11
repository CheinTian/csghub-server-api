# types.SandboxCreateRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environments` | object | No |  |
| `image` | string | Yes |  |
| `min_cpu` | string | No |  |
| `min_memory` | string | No |  |
| `port` | integer | No |  |
| `readiness_probe` | [types.SandboxReadinessProbe](types-SandboxReadinessProbe.md) | No |  |
| `resource_id` | integer | No |  |
| `sandbox_name` | string | Yes |  |
| `timeout` | integer | No |  |
| `volumes` | types.SandboxVolume[] | No |  |

