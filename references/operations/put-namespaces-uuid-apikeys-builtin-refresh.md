# PUT /namespaces/{uuid}/apikeys/builtin/refresh

**Resource:** [API Key](../resources/API-Key.md)
**Refresh builtin API key for an organization or user namespace**
**Operation ID:** `put--namespaces-{uuid}-apikeys-builtin-refresh`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | organization or user namespace uuid |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden - user is not org admin |
| 500 | Internal server error |

## Security

- **ApiKey**
