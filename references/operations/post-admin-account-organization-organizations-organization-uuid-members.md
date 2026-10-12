# POST /admin/account/organization/organizations/{organization_uuid}/members

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**Add organization members for administration**
**Operation ID:** `post--admin-account-organization-organizations-{organization_uuid}-members`

Requires account/organization permission at both services. Original payloads, business validation and downstream responses are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Organization UUID |

## Request Body

Organization operation payload

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AddOrganizationMembersReq](../schemas/types-AddOrganizationMembersReq/types-AddOrganizationMembersReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 409 | The operation would remove the organization's last administrator role |
| 500 | Internal Server Error |

## Security

- **ApiKey**
