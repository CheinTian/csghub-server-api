# POST /agent/credentials/{credential_name}/rotate

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**Rotate an agent credential secret**
**Operation ID:** `post--agent-credentials-{credential_name}-rotate`

Rotate the secret for a credential owned by the current user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `credential_name` | path | string | Yes | credential name |

## Request Body

rotate credential request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.RotateCredentialRequest](../schemas/types-RotateCredentialRequest/types-RotateCredentialRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 500 | Internal server error |

## Security

- **ApiKey**
