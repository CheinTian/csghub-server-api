# PUT /admin/common/user/{identifier}

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Update a profile from the administrator navigation bar**
**Operation ID:** `put--admin-common-user-{identifier}`

Requires an active administrator role; original business authorization and data scope are preserved. Role assignments use administrator role APIs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | string | Yes | User UUID |
| `type` | query | enum: uuid | No | Legacy parameter; updates resolve identifier as a UUID |

## Request Body

Profile fields

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateUserRequest](../schemas/types-UpdateUserRequest/types-UpdateUserRequest.md)

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
