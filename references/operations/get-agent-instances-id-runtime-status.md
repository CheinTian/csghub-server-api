# GET /agent/instances/{id}/runtime-status

**Resource:** [Agent](../resources/Agent.md)
**Get logical agent runtime status for the current actor**
**Operation ID:** `get--agent-instances-{id}-runtime-status`

Returns the caller-scoped runtime readiness without starting or repairing provisioning.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | logical agent instance id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 500 | Internal server error |

