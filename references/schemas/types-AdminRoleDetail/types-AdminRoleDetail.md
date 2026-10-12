# types.AdminRoleDetail

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_delete` | boolean | No | CanDelete controls deletion of the role definition, not user assignments. |
| `created_at` | string | No |  |
| `description` | string | No |  |
| `display_name` | string | No |  |
| `is_admin` | boolean | No | IsAdmin identifies administrator roles in the shared role catalog. |
| `is_builtin` | boolean | No | IsBuiltin identifies a role supplied by the system. |
| `permissions` | types.AdminPermission[] | No |  |
| `role_code` | string | No |  |
| `user_id` | integer | No |  |

