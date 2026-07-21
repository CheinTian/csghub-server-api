# types.FinetuneReq

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `agent` | string | No |  |
| `custom_args` | string | No |  |
| `dataset_id` | string | Yes |  |
| `dataset_revision` | string | No |  |
| `epochs` | integer | No |  |
| `learning_rate` | number | No |  |
| `model_id` | string | Yes |  |
| `namespace` | string | No |  |
| `node_affinity` | [v1.NodeAffinity](v1-NodeAffinity.md) | No |  |
| `pd` | [types.PDConfig](types-PDConfig.md) | No |  |
| `resource_id` | integer | Yes |  |
| `runtime_framework_id` | integer | Yes |  |
| `share_mode` | boolean | No |  |
| `swift_command` | string | No |  |
| `task_desc` | string | No |  |
| `task_name` | string | No |  |
| `tolerations` | types.Toleration[] | No |  |

