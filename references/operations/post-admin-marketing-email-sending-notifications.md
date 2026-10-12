# POST /admin/marketing/email_sending/notifications

**Resource:** [Admin Marketing Email Sending](../resources/Admin-Marketing-Email-Sending.md)
**Send an email operation notification**
**Operation ID:** `post--admin-marketing-email_sending-notifications`

Requires marketing/email_sending administrator permission.

## Request Body

Notification request

**Required:** Yes

**Content Types:** `application/json`

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
