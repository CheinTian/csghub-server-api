# GET /admin/apigateway/commercial_api/tags

**Resource:** [Admin Commercial API](../resources/Admin-Commercial-API.md)
**List tags for commercial API administration**
**Operation ID:** `get--admin-apigateway-commercial_api-tags`

Requires apigateway/commercial_api administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scope` | query | string | No | Repository scope |
| `category` | query | string | No | Tag category |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
