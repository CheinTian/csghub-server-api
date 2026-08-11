# GET /agent/shared/instance

**Resource:** [Agent](../resources/Agent.md)
**Get shared agent instance**
**Operation ID:** `get--agent-shared-instance`

Fetch public information and the Sandbox proxy name for a shared agent instance

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `share_uuid` | query | string | Yes | Share UUID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 404 | Not found |
| 500 | Internal server error |

