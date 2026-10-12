# POST /admin/asset/skill/recom/opweight

**Resource:** [Admin Asset Skill](../resources/Admin-Asset-Skill.md)
**Update recommendation weight for skill administration**
**Operation ID:** `post--admin-asset-skill-recom-opweight`

Requires asset/skill permission and a target repository whose stored type is skill; a type mismatch returns 403 without updating weights.

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
