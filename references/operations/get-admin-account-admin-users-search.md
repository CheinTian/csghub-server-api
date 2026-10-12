# GET /admin/account/admin/users/search

**Resource:** [Admin Account Admin](../resources/Admin-Account-Admin.md)
**Search users for administrator role assignment**
**Operation ID:** `get--admin-account-admin-users-search`

Requires account/admin permission, independently checked by the user service. Searches all users, including users without administrator roles, and preserves the nested user-list response with numeric user IDs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |
| `search` | query | string | No | Search text |
| `verify_status` | query | string | No | Verification status |
| `labels` | query | string[] | No | User labels |
| `exact_match` | query | boolean | No | Match the search text exactly |
| `sort_by` | query | string | No | Sort field |
| `sort_order` | query | string | No | Sort direction |

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
