# PUT /admin/account/organization/organizations/{organization_uuid}/members/{user_uuid}

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**Update an organization member role for administration**
**Operation ID:** `put--admin-account-organization-organizations-{organization_uuid}-members-{user_uuid}`

Requires account/organization permission at both services. Original payloads, business validation and downstream responses are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Organization UUID |
| `user_uuid` | path | string | Yes | User UUID |

## Request Body

Organization operation payload

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateOrganizationMemberRoleReq](../schemas/types-UpdateOrganizationMemberRoleReq/types-UpdateOrganizationMemberRoleReq.md)

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
