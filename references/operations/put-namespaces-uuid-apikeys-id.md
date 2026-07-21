# PUT /namespaces/{uuid}/apikeys/{id}

**Resource:** [API Key](../resources/API-Key.md)
**Update an API key for an organization or user**
**Operation ID:** `put--namespaces-{uuid}-apikeys-{id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | organization or user namespace uuid |
| `id` | path | string | Yes | API key id |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateAPIKeyRequest](../schemas/types-UpdateAPIKeyRequest/types-UpdateAPIKeyRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden - user is not org admin |
| 500 | Internal server error |

## Security

- **ApiKey**
