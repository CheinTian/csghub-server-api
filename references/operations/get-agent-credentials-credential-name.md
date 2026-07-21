# GET /agent/credentials/{credential_name}

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**Get an agent credential**
**Operation ID:** `get--agent-credentials-{credential_name}`

Get a credential by credential name for the current user. Secret material is never returned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `credential_name` | path | string | Yes | credential name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 500 | Internal server error |

## Security

- **ApiKey**
