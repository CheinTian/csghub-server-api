# GET /organizations/mine

**Resource:** [OrganizationUnit](../resources/OrganizationUnit.md)
**Get the visible hierarchy root organization**
**Operation ID:** `get--organizations-mine`

Returns the active hierarchy root as an array for platform admins or members of its organization tree. Returns an empty array when no root exists or access is denied.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not Found |
| 500 | Internal Server Error |

## Security

- **ApiKey**
