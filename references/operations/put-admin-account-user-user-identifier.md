# PUT /admin/account/user/user/{identifier}

**Resource:** [Admin Account User](../resources/Admin-Account-User.md)
**Update a user for account administration**
**Operation ID:** `put--admin-account-user-user-{identifier}`

Requires account/user administrator permission. Role assignments use administrator role APIs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | string | Yes | User UUID |

## Request Body

Profile fields

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateUserRequest](../schemas/types-UpdateUserRequest/types-UpdateUserRequest.md)

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
