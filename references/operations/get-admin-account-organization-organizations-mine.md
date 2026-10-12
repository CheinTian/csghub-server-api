# GET /admin/account/organization/organizations/mine

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**List active root organizations for account administration**
**Operation ID:** `get--admin-account-organization-organizations-mine`

Requires account/organization administrator permission.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
