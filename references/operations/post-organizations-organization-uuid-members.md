# POST /organizations/{organization_uuid}/members

**Resource:** [OrganizationUnitMember](../resources/OrganizationUnitMember.md)
**Add users to an organization**
**Operation ID:** `post--organizations-{organization_uuid}-members`

Creates memberships or replaces existing roles in hierarchy mode.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Organization UUID |

## Request Body

User UUIDs and organization role

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AddOrganizationMembersReq](../schemas/types-AddOrganizationMembersReq/types-AddOrganizationMembersReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |
| 409 | The operation would replace the organization's last administrator role |

## Security

- **ApiKey**
