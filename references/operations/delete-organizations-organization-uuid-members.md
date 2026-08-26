# DELETE /organizations/{organization_uuid}/members

**Resource:** [OrganizationUnitMember](../resources/OrganizationUnitMember.md)
**Remove users from an organization**
**Operation ID:** `delete--organizations-{organization_uuid}-members`

Removes memberships only from the organization identified by the path.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Organization UUID |

## Request Body

User UUIDs

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.RemoveOrganizationMembersReq](../schemas/types-RemoveOrganizationMembersReq/types-RemoveOrganizationMembersReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |
| 409 | The operation would remove the organization's last administrator |

## Security

- **ApiKey**
