# DELETE /admin/academy/collection/collections/{id}

**Resource:** [Admin Academy Collection](../resources/Admin-Academy-Collection.md)
**Delete a collection**
**Operation ID:** `delete--admin-academy-collection-collections-{id}`

Requires academy/collection; query parameters, body, and downstream responses are preserved.

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
