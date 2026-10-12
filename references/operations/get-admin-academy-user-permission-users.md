# GET /admin/academy/user_permission/users

**Resource:** [Admin Academy User Permission](../resources/Admin-Academy-User-Permission.md)
**Read /users for academy/user_permission administration**
**Operation ID:** `get--admin-academy-user_permission-users`

Requires academy/user_permission administrator permission; original query parameters are preserved. Returns only id, uuid, username, nickname, and avatar.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |
| `search` | query | string | No | Search text |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
