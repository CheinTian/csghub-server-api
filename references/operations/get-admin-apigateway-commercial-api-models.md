# GET /admin/apigateway/commercial_api/models

**Resource:** [Admin Commercial API](../resources/Admin-Commercial-API.md)
**List models for commercial API administration**
**Operation ID:** `get--admin-apigateway-commercial_api-models`

Requires apigateway/commercial_api administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Page number |
| `search` | query | string | No | Search text |

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
