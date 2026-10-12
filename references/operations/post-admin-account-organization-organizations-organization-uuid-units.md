# POST /admin/account/organization/organizations/{organization_uuid}/units

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**Create an organization department for administration**
**Operation ID:** `post--admin-account-organization-organizations-{organization_uuid}-units`

Requires account/organization permission at both services. Original payloads, business validation and downstream responses are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Organization UUID |

## Request Body

Organization operation payload

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateOrganizationUnitReq](../schemas/types-CreateOrganizationUnitReq/types-CreateOrganizationUnitReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

## Security

- **ApiKey**
