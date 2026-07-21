# POST /claw/api/v1/skills

**Resource:** [ClawHub](../resources/ClawHub.md)
**Publish skill for ClawHub**
**Operation ID:** `post--claw-api-v1-skills`

Publish a new skill or version for ClawHub

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `payload` | string | Yes | JSON payload with skill metadata |
| `files` | string (binary) | Yes | skill files |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[types.ClawHubPublishSkillResponse](../schemas/types-ClawHubPublishSkillResponse/types-ClawHubPublishSkillResponse.md)

