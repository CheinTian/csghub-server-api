# GET /namespaces/{uuid}/apikeys

**Resource:** [API Key](../resources/API-Key.md)
**Get all API keys for an organization or user**
**Operation ID:** `get--namespaces-{uuid}-apikeys`

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
