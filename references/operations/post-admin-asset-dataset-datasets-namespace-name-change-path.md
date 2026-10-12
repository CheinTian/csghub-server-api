# POST /admin/asset/dataset/datasets/{namespace}/{name}/change_path

**Resource:** [Admin Asset Dataset](../resources/Admin-Asset-Dataset.md)
**Change a dataset path for asset administration**
**Operation ID:** `post--admin-asset-dataset-datasets-{namespace}-{name}-change_path`

Requires asset/dataset administrator permission.

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
