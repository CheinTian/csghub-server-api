# types.CreateMirrorRepoReq

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `access_token` | string | No | AccessToken is the upstream Git HTTP access token. |
| `branch` | string | No |  |
| `create_target_repo` | boolean | No | CreateTargetRepo controls target repository creation. Nil selects automatically,
true requires a new target, and false requires an existing target. |
| `current_user` | string | No |  |
| `description` | string | No |  |
| `fork_name` | string | No |  |
| `fork_namespace` | string | No | fork repo, local namespace/name |
| `license` | string | No |  |
| `mcp_server_attributes` | object | No | MCP only |
| `mirror_source_id` | integer | No | source id for HF,github etc |
| `priority` | object | No | Priority controls scheduling order within the selected mirror queue. |
| `private` | boolean | No |  |
| `repo_type` | object | Yes | repo basic info |
| `source_name` | string | Yes |  |
| `source_namespace` | string | Yes |  |
| `source_url` | string | Yes | mirror source info |
| `urgent` | boolean | No | Urgent routes the initial synchronization through the urgent mirror queues. |
| `username` | string | No | Username is the upstream Git HTTP username. |

