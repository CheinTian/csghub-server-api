# GET /admin/account/user/users

**Resource:** [Admin Account User](../resources/Admin-Account-User.md)
**List users for account administration**
**Operation ID:** `get--admin-account-user-users`

Requires account/user administrator permission, independently checked by the user service.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |
| `search` | query | string | No | Search text |
| `verify_status` | query | string | No | Verification status |

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
