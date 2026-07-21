# GET /claw/api/v1/skills/{slug}

**Resource:** [ClawHub](../resources/ClawHub.md)
**Get skill detail for ClawHub install**
**Operation ID:** `get--claw-api-v1-skills-{slug}`

Get skill metadata for ClawHub install

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slug` | path | string | Yes | skill slug |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[types.ClawHubSkillResponse](../schemas/types-ClawHubSkillResponse/types-ClawHubSkillResponse.md)

