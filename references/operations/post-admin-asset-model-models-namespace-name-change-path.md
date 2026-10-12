# POST /admin/asset/model/models/{namespace}/{name}/change_path

**Resource:** [Admin Asset Model](../resources/Admin-Asset-Model.md)
**Change a model path for asset administration**
**Operation ID:** `post--admin-asset-model-models-{namespace}-{name}-change_path`

Requires asset/model administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | Namespace |
| `name` | path | string | Yes | Repository name |

## Request Body

Path change

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.ChangePathReq](../schemas/types-ChangePathReq/types-ChangePathReq.md)

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
