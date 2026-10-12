# DELETE /admin/academy/course/courses/{id}

**Resource:** [Admin Academy Course](../resources/Admin-Academy-Course.md)
**Delete a course**
**Operation ID:** `delete--admin-academy-course-courses-{id}`

Requires academy/course; query parameters, body, and downstream responses are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Resource identifier |

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
