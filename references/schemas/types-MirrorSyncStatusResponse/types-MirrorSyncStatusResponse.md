# types.MirrorSyncStatusResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `failure_reason` | [types.MirrorSyncFailureReason](types-MirrorSyncFailureReason.md) | No |  |
| `mirror_id` | integer | No |  |
| `phase` | [types.MirrorSyncPhase](types-MirrorSyncPhase.md) | No |  |
| `progress` | integer | No |  |
| `repo_ready` | boolean | No |  |
| `repository_id` | integer | No |  |
| `retrying` | boolean | No |  |
| `status` | [types.MirrorTaskStatus](types-MirrorTaskStatus.md) | No |  |
| `superseded` | boolean | No |  |
| `task_id` | integer | No |  |
| `terminal` | boolean | No |  |
| `updated_at` | string | No |  |

