# POST /admin/account/admin/me/permissions/check

**Resource:** [Admin Account Administrator](../resources/Admin-Account-Administrator.md)
**Check current user's administrator permissions**
**Operation ID:** `post--admin-account-admin-me-permissions-check`

Requires login only at the route. JSON body is limited to 64 KiB. Checks live administrator grants with PlatformAdmin edition policy: CE requires global *; EE/SaaS use OR for multiple requirements. Does not authorize subsequent requests or set business bypass markers.

## Request Body

Non-empty route requirements; any, *, or concrete module/submodule codes

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AdminPermissionCheckRequest](../schemas/types-AdminPermissionCheckRequest/types-AdminPermissionCheckRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

## Security

- **ApiKey**
