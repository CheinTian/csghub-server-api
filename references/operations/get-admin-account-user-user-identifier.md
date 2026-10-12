# GET /admin/account/user/user/{identifier}

**Resource:** [Admin Account User](../resources/Admin-Account-User.md)
**Get a user for account administration**
**Operation ID:** `get--admin-account-user-user-{identifier}`

Requires account/user administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | string | Yes | Username |

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
