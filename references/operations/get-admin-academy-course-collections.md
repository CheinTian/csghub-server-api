# GET /admin/academy/course/collections

**Resource:** [Admin Academy Course](../resources/Admin-Academy-Course.md)
**List collections for the course editor**
**Operation ID:** `get--admin-academy-course-collections`

Requires academy/course; query parameters, body, and downstream responses are preserved.

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
