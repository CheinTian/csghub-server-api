# POST /agent/credentials/runtime/session/revoke

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**Revoke a runtime credential session**
**Operation ID:** `post--agent-credentials-runtime-session-revoke`

Revoke all unexpired credential grants for the runtime session carried by the runtime credential token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `Authorization` | header | string | Yes | Bearer runtime_credential_token |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

