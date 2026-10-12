# POST /admin/common/user/email-verification-code/{email}

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Send a profile email verification code**
**Operation ID:** `post--admin-common-user-email-verification-code-{email}`

Requires an active administrator role; original business authorization and data scope are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `email` | path | string | Yes | Email address |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
