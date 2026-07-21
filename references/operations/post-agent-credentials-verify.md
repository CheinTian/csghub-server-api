# POST /agent/credentials/verify

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**Verify an agent credential connection**
**Operation ID:** `post--agent-credentials-verify`

Make a live API call to the external service to verify the provided credential works. Does not persist anything.

## Request Body

verify credential request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.VerifyCredentialRequest](../schemas/types-VerifyCredentialRequest/types-VerifyCredentialRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 422 | Verification failed |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
