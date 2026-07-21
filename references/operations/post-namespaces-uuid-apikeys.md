# POST /namespaces/{uuid}/apikeys

**Resource:** [API Key](../resources/API-Key.md)
**Create an API key for an organization or user**
**Operation ID:** `post--namespaces-{uuid}-apikeys`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | organization or user namespace uuid |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateAPIKeyRequest](../schemas/types-CreateAPIKeyRequest/types-CreateAPIKeyRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden - user is not org admin |
| 500 | Internal server error |

## Security

- **ApiKey**
