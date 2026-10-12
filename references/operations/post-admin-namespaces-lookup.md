# POST /admin/namespaces/lookup

**Resource:** [Namespace](../resources/Namespace.md)
**Get namespace info by UUIDs.**
**Operation ID:** `post--admin-namespaces-lookup`

Requires apigateway/token_plan administrator permission, independently verified by the User service.

## Request Body

namespace uuids

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

Array

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal server error |

## Security

- **ApiKey**
