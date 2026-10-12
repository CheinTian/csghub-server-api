# POST /admin/academy/course/courses

**Resource:** [Admin Academy Course](../resources/Admin-Academy-Course.md)
**Create a course**
**Operation ID:** `post--admin-academy-course-courses`

Requires academy/course; query parameters, body, and downstream responses are preserved.

## Request Body

Academy service operation payload

**Required:** Yes

**Content Types:** `application/json`

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
