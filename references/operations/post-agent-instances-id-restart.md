# POST /agent/instances/{id}/restart

**Resource:** [Agent](../resources/Agent.md)
**Restart an agent instance in place**
**Operation ID:** `post--agent-instances-{id}-restart`

Recreate an agent instance's backing sandbox on its current hardware resource (csgclaw only)

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
