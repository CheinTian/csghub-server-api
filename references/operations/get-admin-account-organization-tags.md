# GET /admin/account/organization/tags

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**List organization tags for account administration**
**Operation ID:** `get--admin-account-organization-tags`

Requires account/organization administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scope` | query | enum: organization | No | Tag scope |
| `category` | query | string | No | Tag category |

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
