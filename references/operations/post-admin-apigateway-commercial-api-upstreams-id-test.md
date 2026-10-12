# POST /admin/apigateway/commercial_api/upstreams/{id}/test

**Resource:** [Admin Commercial API](../resources/Admin-Commercial-API.md)
**Test an upstream for commercial API administration**
**Operation ID:** `post--admin-apigateway-commercial_api-upstreams-{id}-test`

Requires apigateway/commercial_api administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Upstream ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
