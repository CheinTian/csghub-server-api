# GET /agent/credentials/runtime/{credential_name}

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**Get runtime credential material**
**Operation ID:** `get--agent-credentials-runtime-{credential_name}`

Exchange a runtime credential token for granted credential material by credential name.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `Authorization` | header | string | Yes | Bearer runtime_credential_token |
| `credential_name` | path | string | Yes | credential name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal server error |

