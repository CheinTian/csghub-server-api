# PATCH /agent/credentials/{credential_name}

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**Update an agent credential**
**Operation ID:** `patch--agent-credentials-{credential_name}`

Update mutable credential metadata for the current user. Only description and metadata are mutable; provider, auth_type, credential_name, and secret material are immutable here.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `credential_name` | path | string | Yes | credential name |

## Request Body

update credential request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateCredentialRequest](../schemas/types-UpdateCredentialRequest/types-UpdateCredentialRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 500 | Internal server error |

## Security

- **ApiKey**
