# PUT /organizations/{organization_uuid}

**Resource:** [OrganizationUnit](../resources/OrganizationUnit.md)
**Update organization fields**
**Operation ID:** `put--organizations-{organization_uuid}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Top-level or child organization UUID |

## Request Body

Mutable organization fields

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateOrganizationUnitReq](../schemas/types-UpdateOrganizationUnitReq/types-UpdateOrganizationUnitReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |

## Security

- **ApiKey**
