# POST /agent/instances/{id}/suspend

**Resource:** [Agent](../resources/Agent.md)
**Suspend an agent instance**
**Operation ID:** `post--agent-instances-{id}-suspend`

Suspend an agent instance's backing sandbox without deleting it (csgclaw only)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | Instance ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 500 | Internal server error |

## Security

- **ApiKey**
