# DELETE /admin/account/admin/users/{user_id}/roles/{role_code}

**Resource:** [Admin Account Administrator](../resources/Admin-Account-Administrator.md)
**Remove an administrator role**
**Operation ID:** `delete--admin-account-admin-users-{user_id}-roles-{role_code}`

Requires account/admin administrator permission. At least one active user must retain administrator management permission through an administrator role. EE and SaaS accept account/admin, account/* or *; CE requires a remaining global * grant. The operator is taken from the authenticated request context. Repeated removal succeeds. CE can revoke any administrator role with a global * grant, regardless of its name.

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
| 409 | The last administrator management grant cannot be revoked |
| 500 | Internal Server Error |

## Security

- **ApiKey**
