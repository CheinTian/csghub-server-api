# GET /admin/account/user/accounting/credit/{id}/balance

**Resource:** [Admin Account User](../resources/Admin-Account-User.md)
**Get user balance for account administration**
**Operation ID:** `get--admin-account-user-accounting-credit-{id}-balance`

Requires account/user administrator permission and an active personal user UUID; organization UUIDs are rejected with 403 before any Accounting service call.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Active personal user UUID |

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
