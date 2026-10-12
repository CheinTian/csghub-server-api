# POST /admin/asset/space/recom/opweight

**Resource:** [Admin Asset Space](../resources/Admin-Asset-Space.md)
**Update recommendation weight for space administration**
**Operation ID:** `post--admin-asset-space-recom-opweight`

Requires asset/space permission and a target repository whose stored type is space; a type mismatch returns 403 without updating weights.

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
