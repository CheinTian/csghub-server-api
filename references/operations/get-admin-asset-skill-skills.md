# GET /admin/asset/skill/skills

**Resource:** [Admin Asset Skill](../resources/Admin-Asset-Skill.md)
**List skill resources for asset administration**
**Operation ID:** `get--admin-asset-skill-skills`

Requires asset/skill administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | search text |
| `sort` | query | string | No | sort by |
| `source` | query | enum: opencsg, huggingface, local | No | source |
| `per` | query | integer | No | per |
| `page` | query | integer | No | per page |

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
