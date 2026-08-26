# GET /organizations/{organization_uuid}/units

**Resource:** [OrganizationUnit](../resources/OrganizationUnit.md)
**List direct child organizations**
**Operation ID:** `get--organizations-{organization_uuid}-units`

Lists the direct children of a top-level or child organization without recursively returning deeper descendants.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Top-level or child organization UUID |
| `per` | query | integer | No | Page size |
| `page` | query | integer | No | Page number |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **ApiKey**
