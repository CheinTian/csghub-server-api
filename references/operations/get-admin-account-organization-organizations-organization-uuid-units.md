# GET /admin/account/organization/organizations/{organization_uuid}/units

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**List organization units for account administration**
**Operation ID:** `get--admin-account-organization-organizations-{organization_uuid}-units`

Requires account/organization administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_uuid` | path | string | Yes | Organization UUID |
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
