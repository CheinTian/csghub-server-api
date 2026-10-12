# POST /agent/instances/ui-spaces

**Resource:** [Agent](../resources/Agent.md)
**Create a custom UI space for csgclaw agents**
**Operation ID:** `post--agent-instances-ui-spaces`

Create a public space seeded with the platform-pinned agent UI framework. When name is omitted, the server auto-generates a unique name (agent-ui-<random suffix>) under the given namespace. Compute resource is auto-selected (free resources first). The space is tagged task/agent-ui and becomes selectable via ui-options once running.

## Request Body

Custom UI space data

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateAgentUISpaceReq](../schemas/types-CreateAgentUISpaceReq/types-CreateAgentUISpaceReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
