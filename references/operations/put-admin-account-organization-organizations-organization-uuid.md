# PUT /admin/account/organization/organizations/{organization_uuid}

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**Update organization fields for administration**
**Operation ID:** `put--admin-account-organization-organizations-{organization_uuid}`

Requires account/organization permission at both services. Original payloads, business validation and downstream responses are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Top-level or child organization UUID |

## Request Body

Organization operation payload

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateOrganizationUnitReq](../schemas/types-UpdateOrganizationUnitReq/types-UpdateOrganizationUnitReq.md)

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
