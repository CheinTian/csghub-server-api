# GET /token/{token_value}/quotas

**Resource:** [Access token](../resources/Access-token.md)
**Get all quotas for an API key**
**Operation ID:** `get--token-{token_value}-quotas`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token_value` | path | string | Yes | API key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
