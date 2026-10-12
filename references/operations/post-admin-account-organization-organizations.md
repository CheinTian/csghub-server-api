# POST /admin/account/organization/organizations

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**Create an organization for account administration**
**Operation ID:** `post--admin-account-organization-organizations`

Requires account/organization administrator permission.

## Request Body

Organization fields

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateOrgReq](../schemas/types-CreateOrgReq/types-CreateOrgReq.md)

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
