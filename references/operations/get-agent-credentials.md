# GET /agent/credentials

**Resource:** [AgentCredential](../resources/AgentCredential.md)
**List agent credentials**
**Operation ID:** `get--agent-credentials`

List credentials for the current user. Secret material is never returned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | search by credential name |
| `per` | query | integer | No | per |
| `page` | query | integer | No | page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 500 | Internal server error |

## Security

- **ApiKey**
