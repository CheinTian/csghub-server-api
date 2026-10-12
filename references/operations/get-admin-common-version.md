# GET /admin/common/version

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Get the server version for the administrator navigation bar**
**Operation ID:** `get--admin-common-version`

Requires an active administrator role; original business authorization and data scope are preserved.

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
