# POST /agent/credentials

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**Create an agent credential**
**Operation ID:** `post--agent-credentials`

Create a credential for the current user. Secret material is stored by the configured credential secret backend and is not returned.

## Request Body

credential request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateCredentialRequest](../schemas/types-CreateCredentialRequest/types-CreateCredentialRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 500 | Internal server error |

## Security

- **ApiKey**
