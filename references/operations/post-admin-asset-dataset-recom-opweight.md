# POST /admin/asset/dataset/recom/opweight

**Resource:** [Admin Asset Dataset](../resources/Admin-Asset-Dataset.md)
**Update recommendation weight for dataset administration**
**Operation ID:** `post--admin-asset-dataset-recom-opweight`

Requires asset/dataset permission and a target repository whose stored type is dataset; a type mismatch returns 403 without updating weights.

## Request Body

Repository ID and recommendation weight

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [handler.SetOpWeight.SetOpWeightReq](../schemas/handler-SetOpWeight-SetOpWeightReq/handler-SetOpWeight-SetOpWeightReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
