# types.User

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar` | string | No |  |
| `bio` | string | No |  |
| `can_change_username` | boolean | No |  |
| `created_at` | string | No |  |
| `email` | string | No |  |
| `homepage` | string | No |  |
| `id` | integer | No |  |
| `is_admin` | boolean | No | Admin identifies membership in an existing administrator role, regardless of its grants. |
| `is_super_admin` | boolean | No | SuperAdmin identifies an active role assignment granting the global wildcard permission. |
| `labels` | string[] | No |  |
| `last_login_at` | string | No |  |
| `namespaces` | types.Namespace[] | No |  |
| `nickname` | string | No |  |
| `orgs` | types.Organization[] | No |  |
| `phone` | string | No |  |
| `phone_area` | string | No |  |
| `roles` | string[] | No |  |
| `tags` | types.RepoTag[] | No |  |
| `username` | string | No |  |
| `uuid` | string | No |  |
| `verify_status` | string | No |  |

