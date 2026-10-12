# GET /admin/asset/skill/skills/{namespace}/{name}/size/{branch}

**Resource:** [Admin Asset Skill](../resources/Admin-Asset-Skill.md)
**Size skill resources for asset administration**
**Operation ID:** `get--admin-asset-skill-skills-{namespace}-{name}-size-{branch}`

Requires asset/skill administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | repo owner name |
| `name` | path | string | Yes | repo name |
| `branch` | path | string | Yes | branch name |

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
