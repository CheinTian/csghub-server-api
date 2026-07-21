# GET /namespaces/{uuid}/apikeys/builtin

**Resource:** [API Key](../resources/API-Key.md)
**Get or create builtin API key for an organization or user namespace**
**Operation ID:** `get--namespaces-{uuid}-apikeys-builtin`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | organization or user namespace uuid |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
