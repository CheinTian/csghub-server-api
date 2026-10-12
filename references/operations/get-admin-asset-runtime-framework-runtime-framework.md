# GET /admin/asset/runtime_framework/runtime_framework

**Resource:** [Admin asset/runtime_framework](../resources/Admin-asset-runtime-framework.md)
**List runtime_framework for asset/runtime_framework administration**
**Operation ID:** `get--admin-asset-runtime_framework-runtime_framework`

Requires asset/runtime_framework administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `deploy_type` | query | enum: 1, 2, 3... | No | deploy_type |

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
