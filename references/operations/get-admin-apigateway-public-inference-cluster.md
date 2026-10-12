# GET /admin/apigateway/public_inference/cluster

**Resource:** [Admin Apigateway Public Inference](../resources/Admin-Apigateway-Public-Inference.md)
**Read /cluster for apigateway/public_inference administration**
**Operation ID:** `get--admin-apigateway-public_inference-cluster`

Requires apigateway/public_inference administrator permission; original query parameters are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scope` | query | enum: all | No | Scope of cluster |

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
