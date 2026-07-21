# database.AccessToken

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `application` | object | No | example: csghub, starship |
| `created_at` | string | No |  |
| `deletedAt` | string | No |  |
| `expired_at` | string | No |  |
| `git_id` | integer | No |  |
| `id` | integer | No |  |
| `is_active` | boolean | No |  |
| `name` | string | No |  |
| `ns_uuid` | string | No | namespace uuid for gateway api key |
| `permission` | string | No |  |
| `token` | string | No | access token value or api key value |
| `token_type` | [types.AccessTokenType](types-AccessTokenType.md) | No |  |
| `updated_at` | string | No |  |
| `user` | [database.User](database-User.md) | No |  |
| `user_id` | integer | No |  |

