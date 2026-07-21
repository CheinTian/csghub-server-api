# DELETE /namespace/{uuid}/apikeys/{id}

**Resource:** [API Key](../resources/API-Key.md)
**Delete an API key for an organization or user**
**Operation ID:** `delete--namespace-{uuid}-apikeys-{id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | API key id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden - user is not org admin |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
