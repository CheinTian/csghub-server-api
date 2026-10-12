# GET /admin/account/organization/organization/{name}

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**Get an organization for account administration**
**Operation ID:** `get--admin-account-organization-organization-{name}`

Requires account/organization administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | path | string | Yes | Organization path |

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
