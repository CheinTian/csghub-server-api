# GET /admin/account/user/user/verify/{uuid}

**Resource:** [Admin Account User](../resources/Admin-Account-User.md)
**Get user verification for account administration**
**Operation ID:** `get--admin-account-user-user-verify-{uuid}`

Requires account/user administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | User UUID |

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
