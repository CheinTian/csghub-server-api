# types.ArgoWorkFlowRes

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dataset_revisions` | string[] | No |  |
| `datasets` | string[] | No |  |
| `download_url` | string | No |  |
| `end_time` | string | No |  |
| `failures_url` | string | No |  |
| `framework_config` | string | No |  |
| `hardware` | [types.HardWare](types-HardWare.md) | No |  |
| `id` | integer | No |  |
| `image` | string | No |  |
| `namespace` | string | No | Namespace of the workflow |
| `pay_mode` | [types.PayMode](types-PayMode.md) | No |  |
| `reason` | string | No |  |
| `repo_ids` | string[] | No |  |
| `repo_revisions` | string[] | No | RepoRevisions is index-aligned with RepoIds; DatasetRevisions with Datasets. |
| `repo_type` | string | No |  |
| `resource_id` | integer | No |  |
| `resource_name` | string | No |  |
| `result_url` | string | No |  |
| `start_time` | string | No |  |
| `status` | [v1alpha1.WorkflowPhase](v1alpha1-WorkflowPhase.md) | No |  |
| `submit_time` | string | No |  |
| `task_desc` | string | No |  |
| `task_id` | string | No |  |
| `task_name` | string | No |  |
| `task_type` | [types.TaskType](types-TaskType.md) | No |  |
| `username` | string | No |  |

