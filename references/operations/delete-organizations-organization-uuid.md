# DELETE /organizations/{organization_uuid}

**Resource:** [OrganizationUnit](../resources/OrganizationUnit.md)
**Delete a top-level organization hierarchy**
**Operation ID:** `delete--organizations-{organization_uuid}`

Soft-deletes a root organization, all descendant organizations, namespaces, units, and memberships, then deletes their SSO identities.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Top-level organization UUID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

## Security

- **ApiKey**
