# POST /admin/common/jwt/token

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Refresh the current administrator JWT**
**Operation ID:** `post--admin-common-jwt-token`

Independently requires administrator membership. UUID and old_token must match the authenticated caller; the existing edition-specific expiry policy is preserved.

## Request Body

Current user UUID and existing JWT

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.RefreshJWTReq](../schemas/types-RefreshJWTReq/types-RefreshJWTReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

## Security

- **ApiKey**
