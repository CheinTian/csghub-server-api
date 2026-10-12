# GET /admin/account/organization/organizations

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**List organizations for account administration**
**Operation ID:** `get--admin-account-organization-organizations`

Requires account/organization administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |
| `search` | query | string | No | Search text |
| `org_type` | query | string | No | Organization type filter |
| `verify_status` | query | string | No | Verification status filter |
| `tag` | query | string | No | Tag name filter |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

## Security

- **ApiKey**
