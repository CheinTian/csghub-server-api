# types.AgentKnowledgeBaseDetail

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar` | string | No |  |
| `can_manage` | boolean | No | CanManage reports whether the caller may update or delete the KB record
(ReBAC can_admin, same value as editable). |
| `can_write` | boolean | No | CanWrite reports whether the caller may write KB content through the
management proxy (ReBAC can_write). |
| `content_id` | string | No |  |
| `created_at` | string | No |  |
| `description` | string | No |  |
| `editable` | boolean | No |  |
| `id` | integer | No |  |
| `is_pinned` | boolean | No | Whether the knowledge base is pinned by the user |
| `metadata` | object | No |  |
| `name` | string | No |  |
| `namespace_type` | string | No | NamespaceType is the trusted namespace type: "user" or "organization". |
| `namespace_uuid` | string | No | NamespaceUUID is the personal or organization namespace that owns the KB. |
| `owner` | string | No |  |
| `public` | boolean | No |  |
| `type` | [types.AgentKnowledgeBaseType](types-AgentKnowledgeBaseType.md) | No |  |
| `updated_at` | string | No |  |
| `user_uuid` | string | No |  |

