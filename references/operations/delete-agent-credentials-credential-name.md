# DELETE /agent/credentials/{credential_name}

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**Delete an agent credential**
**Operation ID:** `delete--agent-credentials-{credential_name}`

Delete a credential owned by the current user and remove its internal secret when applicable.

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
