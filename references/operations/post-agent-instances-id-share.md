# POST /agent/instances/{id}/share

**Resource:** [Agent](../resources/Agent.md)
**Share a public agent instance**
**Operation ID:** `post--agent-instances-{id}-share`

Create a new anonymous share link for a public agent instance. Each call creates another link.

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
