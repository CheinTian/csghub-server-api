# PUT /organizations/{organization_uuid}/members/{user_uuid}

**Resource:** [OrganizationUnitMember](../resources/OrganizationUnitMember.md)
**Update one organization member role**
**Operation ID:** `put--organizations-{organization_uuid}-members-{user_uuid}`

Updates an existing member's direct role in a top-level or child organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Top-level or child organization UUID |
| `user_uuid` | path | string | Yes | User UUID |

## Request Body

New organization role

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateOrganizationMemberRoleReq](../schemas/types-UpdateOrganizationMemberRoleReq/types-UpdateOrganizationMemberRoleReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |
| 404 | Not Found |
| 409 | The operation would remove the organization's last administrator role |

## Security

- **ApiKey**
