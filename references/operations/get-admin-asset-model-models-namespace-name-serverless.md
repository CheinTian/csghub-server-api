# GET /admin/asset/model/models/{namespace}/{name}/serverless

**Resource:** [Admin Asset Model](../resources/Admin-Asset-Model.md)
**Get /models/:namespace/:name/serverless for asset/model administration**
**Operation ID:** `get--admin-asset-model-models-{namespace}-{name}-serverless`

Requires asset/model administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |

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
