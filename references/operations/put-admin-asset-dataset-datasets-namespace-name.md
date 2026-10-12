# PUT /admin/asset/dataset/datasets/{namespace}/{name}

**Resource:** [Admin Asset Dataset](../resources/Admin-Asset-Dataset.md)
**Update dataset resources for asset administration**
**Operation ID:** `put--admin-asset-dataset-datasets-{namespace}-{name}`

Requires asset/dataset administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateDatasetReq](../schemas/types-UpdateDatasetReq/types-UpdateDatasetReq.md)

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
