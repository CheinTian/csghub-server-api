# GET /claw/api/v1/skills/{slug}/versions/{version}

**Resource:** [ClawHub](../resources/ClawHub.md)
**Get skill version detail for ClawHub install**
**Operation ID:** `get--claw-api-v1-skills-{slug}-versions-{version}`

Get skill metadata for a specified ClawHub version

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slug` | path | string | Yes | skill slug |
| `version` | path | string | Yes | skill version |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[types.ClawHubSkillVersionResponse](../schemas/types-ClawHubSkillVersionResponse/types-ClawHubSkillVersionResponse.md)

