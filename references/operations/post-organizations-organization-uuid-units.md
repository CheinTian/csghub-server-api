# POST /organizations/{organization_uuid}/units

**Resource:** [OrganizationUnit](../resources/OrganizationUnit.md)
**Create an organization department**
**Operation ID:** `post--organizations-{organization_uuid}-units`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Organization UUID |

## Request Body

Department fields

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateOrganizationUnitReq](../schemas/types-CreateOrganizationUnitReq/types-CreateOrganizationUnitReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |
| 500 | Internal Server Error |

## Security

- **ApiKey**
