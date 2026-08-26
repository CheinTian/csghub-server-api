# database.Organization

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string | No |  |
| `deleted_at` | string | No | DeletedAt hides soft-deleted child organizations from normal queries. |
| `description` | string | No |  |
| `git_path` | string | No |  |
| `homepage` | string | No |  |
| `id` | integer | No |  |
| `is_root` | boolean | No | IsRoot marks whether the organization is a top-level organization. |
| `is_unit` | boolean | No | IsUnit marks whether the organization belongs to the hierarchy model. |
| `logo` | string | No |  |
| `name` | string | No |  |
| `namespace` | [database.Namespace](database-Namespace.md) | No |  |
| `namespace_id` | integer | No |  |
| `org_type` | string | No |  |
| `path` | string | No | unique name of the organization |
| `role` | string | No |  |
| `updated_at` | string | No |  |
| `user` | [database.User](database-User.md) | No |  |
| `user_id` | integer | No |  |
| `uuid` | string | No |  |
| `verified` | boolean | No |  |
| `verify_status` | object | No | none, pending, approved, rejected |

