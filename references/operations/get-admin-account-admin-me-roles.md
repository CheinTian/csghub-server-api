# GET /admin/account/admin/me/roles

**Resource:** [Admin Account Administrator](../resources/Admin-Account-Administrator.md)
**List current user's administrator roles**
**Operation ID:** `get--admin-account-admin-me-roles`

Requires AdminPermissionAny. Identity comes only from the authenticated request context; revoked assignments and ordinary roles are excluded. CE returns only roles carrying an active global * grant.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

## Security

- **ApiKey**
