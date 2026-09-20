# types.OrganizationUnit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string | No |  |
| `deleted_at` | string | No |  |
| `depth` | integer | No |  |
| `description` | string | No |  |
| `homepage` | string | No |  |
| `is_hierarchical` | boolean | No | IsHierarchical reports whether this organization belongs to a hierarchy. |
| `is_root` | boolean | No |  |
| `logo` | string | No |  |
| `name` | string | No |  |
| `namespace` | [types.Namespace](types-Namespace.md) | No |  |
| `nickname` | string | No |  |
| `org_type` | string | No |  |
| `organization_uuid` | string | No | OrganizationUUID identifies the real child organization represented by this unit. |
| `parent_unit_uuid` | string | No |  |
| `root_organization_uuid` | string | No | RootOrganizationUUID identifies the top-level organization that owns the tree. |
| `sort_order` | integer | No |  |
| `tags` | types.RepoTag[] | No | Tags contains the organization-scoped tags assigned to this hierarchy unit. |
| `updated_at` | string | No |  |
| `user_id` | integer | No |  |
| `uuid` | string | No | UUID is the stable UUID of the child organization and hierarchy unit. |
| `verified` | boolean | No |  |

