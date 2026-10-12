# POST /admin/apigateway/commercial_api/upstreams

**Resource:** [Admin Commercial API](../resources/Admin-Commercial-API.md)
**Create an upstream for commercial API administration**
**Operation ID:** `post--admin-apigateway-commercial_api-upstreams`

Requires apigateway/commercial_api administrator permission.

## Request Body

Upstream configuration

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateUpstreamReq](../schemas/types-CreateUpstreamReq/types-CreateUpstreamReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
