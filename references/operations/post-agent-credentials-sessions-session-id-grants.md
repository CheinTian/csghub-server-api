# POST /agent/credentials/sessions/{session_id}/grants

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**Create agent credential grants**
**Operation ID:** `post--agent-credentials-sessions-{session_id}-grants`

Grant a runtime agent session temporary access to selected credentials and return a runtime credential token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `session_id` | path | string | Yes | runtime session id |

## Request Body

credential grant request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateTaskCredentialGrantRequest](../schemas/types-CreateTaskCredentialGrantRequest/types-CreateTaskCredentialGrantRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 500 | Internal server error |

## Security

- **ApiKey**
