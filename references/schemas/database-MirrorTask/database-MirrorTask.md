# database.MirrorTask

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after_last_commit_id` | string | No |  |
| `before_last_commit_id` | string | No |  |
| `created_at` | string | No |  |
| `error_message` | string | No |  |
| `finishedAt` | string | No |  |
| `id` | integer | No |  |
| `is_urgent` | boolean | No | IsUrgent reports whether this task was submitted through the urgent queues. |
| `lfs_job_id` | integer | No | LFSJobID stores the River job ID for the Git LFS sync phase. |
| `mirror` | [database.Mirror](database-Mirror.md) | No |  |
| `mirror_id` | integer | No |  |
| `payload` | string | No |  |
| `priority` | [types.MirrorPriority](types-MirrorPriority.md) | No |  |
| `progress` | integer | No |  |
| `repo_job_id` | integer | No | RepoJobID stores the River job ID for the repository sync phase. |
| `retry_count` | integer | No |  |
| `startedAt` | string | No |  |
| `status` | [types.MirrorTaskStatus](types-MirrorTaskStatus.md) | No |  |
| `updated_at` | string | No |  |

