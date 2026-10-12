# GET /admin/account/organization/users

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**Search users for organization membership**
**Operation ID:** `get--admin-account-organization-users`

Requires account/organization administrator permission. Returns only id, uuid, username, nickname, and avatar.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | Username search |
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
