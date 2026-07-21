# PUT /internal/agent/templates/{id}

**Resource:** [Agent](../resources/Agent.md)
**Update an internal agent template**
**Operation ID:** `put--internal-agent-templates-{id}`

Update an internal agent template owned by the system user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | Template ID |

## Request Body

Updated template data

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AgentTemplate](../schemas/types-AgentTemplate/types-AgentTemplate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 404 | Not found |
| 500 | Internal server error |

## Security

- **ApiKey**
