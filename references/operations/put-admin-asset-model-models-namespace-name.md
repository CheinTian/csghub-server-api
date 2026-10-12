# PUT /admin/asset/model/models/{namespace}/{name}

**Resource:** [Admin Asset Model](../resources/Admin-Asset-Model.md)
**Update model resources for asset administration**
**Operation ID:** `put--admin-asset-model-models-{namespace}-{name}`

Requires asset/model administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateModelReq](../schemas/types-UpdateModelReq/types-UpdateModelReq.md)

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
