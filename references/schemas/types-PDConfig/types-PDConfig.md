# types.PDConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `decode` | object | No | Decode holds the parallelism and hardware config for the decode role. |
| `decode_replicas` | integer | No |  |
| `enabled` | boolean | No |  |
| `hpa` | [types.PDHPAConfig](types-PDHPAConfig.md) | No |  |
| `prefill` | object | No | Prefill holds the parallelism and hardware config for the prefill role. |
| `prefill_replicas` | integer | No |  |

