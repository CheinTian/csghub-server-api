# types.Dataset

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_manage` | boolean | No |  |
| `can_write` | boolean | No |  |
| `created_at` | string | No |  |
| `csg_path` | string | No |  |
| `current_application` | [types.DatasetApplication](types-DatasetApplication.md) | No |  |
| `dataset_type` | [types.DatasetType](types-DatasetType.md) | No |  |
| `default_branch` | string | No |  |
| `description` | string | No |  |
| `downloads` | integer | No |  |
| `forked` | boolean | No |  |
| `hf_path` | string | No |  |
| `id` | integer | No |  |
| `is_for_sale` | boolean | No |  |
| `license` | string | No |  |
| `likes` | integer | No |  |
| `mirror_last_updated_at` | string | No |  |
| `mirror_task_status` | [types.MirrorTaskStatus](types-MirrorTaskStatus.md) | No |  |
| `ms_path` | string | No |  |
| `name` | string | No |  |
| `namespace` | [types.Namespace](types-Namespace.md) | No |  |
| `nickname` | string | No |  |
| `path` | string | No |  |
| `price` | number | No |  |
| `private` | boolean | No |  |
| `purchase_task_status` | [types.DatasetPurchaseTaskStatus](types-DatasetPurchaseTaskStatus.md) | No |  |
| `readme` | string | No |  |
| `recom_op_weight` | integer | No |  |
| `related_dataset` | [types.Dataset](types-Dataset.md) | No |  |
| `related_dataset_id` | integer | No |  |
| `repository` | [types.Repository](types-Repository.md) | No |  |
| `repository_id` | integer | No |  |
| `scores` | types.WeightScore[] | No |  |
| `sensitive_check_status` | string | No |  |
| `source` | [types.RepositorySource](types-RepositorySource.md) | No |  |
| `status` | [types.DatasetStatus](types-DatasetStatus.md) | No |  |
| `sync_status` | [types.RepositorySyncStatus](types-RepositorySyncStatus.md) | No |  |
| `tags` | types.RepoTag[] | No |  |
| `updated_at` | string | No |  |
| `url` | string | No |  |
| `user` | [types.User](types-User.md) | No |  |
| `user_likes` | boolean | No |  |
| `user_purchased` | boolean | No |  |
| `xnet_enabled` | boolean | No |  |
| `xnet_migration_progress` | integer | No |  |
| `xnet_migration_status` | [types.XnetMigrationTaskStatus](types-XnetMigrationTaskStatus.md) | No |  |

