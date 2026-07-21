# POST /agent/credentials/{credential_name}/revoke

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**Revoke an agent credential**
**Operation ID:** `post--agent-credentials-{credential_name}-revoke`

Mark a credential owned by the current user as revoked.

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

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
