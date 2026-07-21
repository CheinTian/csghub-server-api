# GET /agent/credentials/sessions/{session_id}/grants

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**List agent credential grants**
**Operation ID:** `get--agent-credentials-sessions-{session_id}-grants`

List credential grants for a runtime session.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `session_id` | path | string | Yes | runtime session id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 500 | Internal server error |

## Security

- **ApiKey**
