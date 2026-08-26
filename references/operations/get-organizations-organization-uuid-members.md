# GET /organizations/{organization_uuid}/members

**Resource:** [OrganizationUnitMember](../resources/OrganizationUnitMember.md)
**List members of an organization**
**Operation ID:** `get--organizations-{organization_uuid}-members`

Lists only direct members of the organization identified by the path, whether it is top-level or a child organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Organization UUID |
| `search` | query | string | No | Case-insensitive username, nickname, or email search |
| `role` | query | string | No | Direct member role filter: all, admin, write, or read |
| `per` | query | integer | No | Page size |
| `page` | query | integer | No | Page number |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |

## Security

- **ApiKey**
