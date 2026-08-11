# types.MirrorSyncSummary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `access_token` | string | No |  |
| `is_urgent` | boolean | No | IsUrgent reports whether the current mirror task uses the urgent queues. |
| `lfs_stage` | [types.MirrorSyncStageSummary](types-MirrorSyncStageSummary.md) | No |  |
| `max_retry_count` | integer | No | MaxRetryCount is the configured maximum retry count and excludes the initial execution. |
| `mirror_id` | integer | No |  |
| `priority` | object | No | Priority is the scheduling priority persisted on the current mirror task. |
| `progress` | integer | No |  |
| `repo_path` | string | No |  |
| `repo_stage` | [types.MirrorSyncStageSummary](types-MirrorSyncStageSummary.md) | No |  |
| `repository_id` | integer | No |  |
| `result` | [types.MirrorSyncResult](types-MirrorSyncResult.md) | No |  |
| `retry_count` | integer | No | RetryCount is the current stage retry count persisted on the mirror task. |
| `retrying` | boolean | No |  |
| `source_url` | string | No |  |
| `status` | [types.MirrorSyncOverallStatus](types-MirrorSyncOverallStatus.md) | No |  |
| `task_id` | integer | No |  |
| `username` | string | No |  |

