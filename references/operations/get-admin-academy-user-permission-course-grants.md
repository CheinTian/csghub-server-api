# GET /admin/academy/user_permission/course_grants

**Resource:** [Admin Academy User Permission](../resources/Admin-Academy-User-Permission.md)
**List user course grants**
**Operation ID:** `get--admin-academy-user_permission-course_grants`

Requires academy/user_permission; query parameters, body, and downstream responses are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
