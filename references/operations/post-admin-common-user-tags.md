# POST /admin/common/user/tags

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Set the current administrator user's industry tags**
**Operation ID:** `post--admin-common-user-tags`

Requires an active administrator role; original business authorization and data scope are preserved.

## Request Body

Industry tag IDs

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

Array

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
