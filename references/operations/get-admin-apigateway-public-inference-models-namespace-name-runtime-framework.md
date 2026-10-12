# GET /admin/apigateway/public_inference/models/{namespace}/{name}/runtime_framework

**Resource:** [Admin Apigateway Public Inference](../resources/Admin-Apigateway-Public-Inference.md)
**Get /models/:namespace/:name/runtime_framework for apigateway/public_inference administration**
**Operation ID:** `get--admin-apigateway-public_inference-models-{namespace}-{name}-runtime_framework`

Requires apigateway/public_inference administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `deploy_type` | query | enum: 0, 1, 2... | No | deploy_type |

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
