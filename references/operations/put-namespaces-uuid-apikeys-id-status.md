# PUT /namespaces/{uuid}/apikeys/{id}/status

**Resource:** [API Key](../resources/API-Key.md)
**Enable or disable an API key for an organization or user**
**Operation ID:** `put--namespaces-{uuid}-apikeys-{id}-status`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | organization or user namespace uuid |
| `id` | path | string | Yes | API key id |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateAPIKeyStatusRequest](../schemas/types-UpdateAPIKeyStatusRequest/types-UpdateAPIKeyStatusRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized - builtin key cannot be disabled |
| 403 | Forbidden - user is not org admin |
| 404 | API key not found |
| 500 | Internal server error |

## Security

- **ApiKey**
