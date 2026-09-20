# types.Organization

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No |  |
| `homepage` | string | No |  |
| `is_hierarchical` | boolean | No | IsHierarchical reports whether this organization belongs to the hierarchy model. |
| `is_root` | boolean | No | IsRoot reports whether this is a top-level organization. |
| `logo` | string | No |  |
| `name` | string | No |  |
| `namespace` | [types.Namespace](types-Namespace.md) | No |  |
| `org_type` | string | No |  |
| `path` | string | No | unique name of the organization |
| `role` | string | No |  |
| `tags` | types.RepoTag[] | No |  |
| `user_id` | integer | No |  |
| `uuid` | string | No |  |
| `verified` | boolean | No |  |
| `verify_status` | string | No |  |

