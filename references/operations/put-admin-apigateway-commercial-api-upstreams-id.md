# PUT /admin/apigateway/commercial_api/upstreams/{id}

**Resource:** [Admin Commercial API](../resources/Admin-Commercial-API.md)
**Update an upstream for commercial API administration**
**Operation ID:** `put--admin-apigateway-commercial_api-upstreams-{id}`

Requires apigateway/commercial_api administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Upstream ID |

## Request Body

Upstream configuration

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateUpstreamReq](../schemas/types-UpdateUpstreamReq/types-UpdateUpstreamReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
