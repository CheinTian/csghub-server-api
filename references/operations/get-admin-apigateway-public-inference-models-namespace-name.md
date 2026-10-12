# GET /admin/apigateway/public_inference/models/{namespace}/{name}

**Resource:** [Admin Apigateway Public Inference](../resources/Admin-Apigateway-Public-Inference.md)
**Get /models/:namespace/:name for apigateway/public_inference administration**
**Operation ID:** `get--admin-apigateway-public_inference-models-{namespace}-{name}`

Requires apigateway/public_inference administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `need_op_weight` | query | boolean | No | need op weight |
| `need_multi_sync` | query | boolean | No | need multi sync |

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
