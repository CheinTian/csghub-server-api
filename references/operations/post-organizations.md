# POST /organizations

**Resource:** [OrganizationUnit](../resources/OrganizationUnit.md)
**Create a top-level organization**
**Operation ID:** `post--organizations`

Creates a root organization, initializes its hierarchy node, and adds the current user as an administrator.

## Request Body

Organization fields

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateOrgReq](../schemas/types-CreateOrgReq/types-CreateOrgReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 500 | Internal Server Error |

## Security

- **ApiKey**
