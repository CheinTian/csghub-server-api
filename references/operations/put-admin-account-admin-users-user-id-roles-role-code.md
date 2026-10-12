# PUT /admin/account/admin/users/{user_id}/roles/{role_code}

**Resource:** [Admin Account Administrator](../resources/Admin-Account-Administrator.md)
**Assign an administrator role**
**Operation ID:** `put--admin-account-admin-users-{user_id}-roles-{role_code}`

Requires account/admin administrator permission. The operator is taken from the authenticated request context. Repeated assignment succeeds. CE can assign only administrator roles with a global * grant, regardless of their names.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | integer | Yes | Positive user ID |
| `role_code` | path | string | Yes | Administrator role code, at most 64 characters without surrounding whitespace |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

## Security

- **ApiKey**
