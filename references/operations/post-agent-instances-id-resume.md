# POST /agent/instances/{id}/resume

**Resource:** [Agent](../resources/Agent.md)
**Resume an agent instance**
**Operation ID:** `post--agent-instances-{id}-resume`

Resume a suspended agent instance's backing sandbox (csgclaw only)

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
