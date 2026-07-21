# types.EvaluationReq

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `api_key` | string | No |  |
| `base_url` | string | No |  |
| `command` | string | No | claw-eval fields |
| `config` | string | No |  |
| `custom_datasets` | string[] | No | custom datasets |
| `datasets` | string[] | No |  |
| `judge_model` | string | No |  |
| `model` | string | No |  |
| `model_id` | string | No |  |
| `model_ids` | string[] | No | for comparison |
| `no_judge` | boolean | No |  |
| `node_affinity` | [v1.NodeAffinity](v1-NodeAffinity.md) | No |  |
| `owner_namespace` | string | No |  |
| `parallel` | integer | No |  |
| `pd` | [types.PDConfig](types-PDConfig.md) | No |  |
| `proxy` | string | No |  |
| `resource_id` | integer | No |  |
| `runtime_framework_id` | integer | No | ArgoWorkFlow framework |
| `share_mode` | boolean | No |  |
| `task_desc` | string | No |  |
| `task_name` | string | No |  |
| `tasks` | string | No |  |
| `tolerations` | types.Toleration[] | No |  |
| `trace_dir` | string | No |  |
| `trials` | integer | No |  |

