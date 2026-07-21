# POST /skills/{namespace}/{name}/publish

**Resource:** [Skill](../resources/Skill.md)
**Publish a skill version**
**Operation ID:** `post--skills-{namespace}-{name}-publish`

publish current skill repository commit as an installable version

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.PublishSkillVersionReq](../schemas/types-PublishSkillVersionReq/types-PublishSkillVersionReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 500 | Internal server error |

## Security

- **ApiKey**
