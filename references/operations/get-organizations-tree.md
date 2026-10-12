# GET /organizations/tree

**Resource:** [OrganizationUnit](../resources/OrganizationUnit.md)
**Get the current hierarchy organization tree**
**Operation ID:** `get--organizations-tree`

Returns status 1 when no top-level organization exists, status 2 when the user has no permission, and status 3 with the active hierarchy tree without member data.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 500 | Internal Server Error |

## Security

- **ApiKey**
