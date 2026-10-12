# GET /admin/account/organization/organization/verify/{name}

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**Get organization verification for account administration**
**Operation ID:** `get--admin-account-organization-organization-verify-{name}`

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
