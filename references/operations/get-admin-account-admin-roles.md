# GET /admin/account/admin/roles

**Resource:** [Admin Account Administrator](../resources/Admin-Account-Administrator.md)
**List administrator roles**
**Operation ID:** `get--admin-account-admin-roles`

Requires AdminPermissionAny with edition policy. CE returns administrator roles carrying a global * grant regardless of their names; EE/SaaS return the complete administrator catalog.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

## Security

- **ApiKey**
