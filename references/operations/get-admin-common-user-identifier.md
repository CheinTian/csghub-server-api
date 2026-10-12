# GET /admin/common/user/{identifier}

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Get a profile for the administrator navigation bar**
**Operation ID:** `get--admin-common-user-{identifier}`

Requires an active administrator role; original business authorization and data scope are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | string | Yes | Username or user UUID |
| `type` | query | enum: uuid | No | Use uuid to resolve a user UUID |

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
