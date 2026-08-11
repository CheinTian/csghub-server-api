# POST /agent/instances/{id}/share

**Resource:** [Agent](../resources/Agent.md)
**Share a public agent instance**
**Operation ID:** `post--agent-instances-{id}-share`

Create an anonymous share for a public agent instance

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Instance ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 500 | Internal server error |

## Security

- **ApiKey**
