# POST /admin/academy/user_permission/users/{user_id}/permissions

**Resource:** [Admin Academy User Permission](../resources/Admin-Academy-User-Permission.md)
**Grant or revoke a user course permission**
**Operation ID:** `post--admin-academy-user_permission-users-{user_id}-permissions`

Requires academy/user_permission; query parameters, body, and downstream responses are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | string | Yes | User UUID |

## Request Body

Academy service operation payload

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
