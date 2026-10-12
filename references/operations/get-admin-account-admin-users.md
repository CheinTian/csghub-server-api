# GET /admin/account/admin/users

**Resource:** [Admin Account Administrator](../resources/Admin-Account-Administrator.md)
**List administrator users**
**Operation ID:** `get--admin-account-admin-users`

Requires account/admin administrator permission. EE/SaaS retain all roles when filtering. CE accepts any global administrator role filter and returns only roles carrying *; filtering module-only roles is forbidden.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `role_code` | query | string | No | Administrator role code, at most 64 characters without surrounding whitespace |
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

## Security

- **ApiKey**
