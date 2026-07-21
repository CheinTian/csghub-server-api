# types.CreateMirrorRepoReq

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `branch` | string | No |  |
| `current_user` | string | No |  |
| `description` | string | No |  |
| `fork_name` | string | No |  |
| `fork_namespace` | string | No | fork repo, local namespace/name |
| `license` | string | No |  |
| `mcp_server_attributes` | object | No | MCP only |
| `mirror_source_id` | integer | No | source id for HF,github etc |
| `private` | boolean | No |  |
| `reject_existing_repo` | boolean | No |  |
| `repo_type` | object | Yes | repo basic info |
| `source_name` | string | Yes |  |
| `source_namespace` | string | Yes |  |
| `source_url` | string | Yes | mirror source info |

