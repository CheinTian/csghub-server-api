# PUT /admin/asset/skill/skills/{namespace}/{name}

**Resource:** [Admin Asset Skill](../resources/Admin-Asset-Skill.md)
**Update skill resources for asset administration**
**Operation ID:** `put--admin-asset-skill-skills-{namespace}-{name}`

Requires asset/skill administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateSkillReq](../schemas/types-UpdateSkillReq/types-UpdateSkillReq.md)

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
