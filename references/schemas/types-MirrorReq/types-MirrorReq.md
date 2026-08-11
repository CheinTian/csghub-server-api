# types.MirrorReq

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `access_token` | string | No | AccessToken is the upstream Git HTTP access token. |
| `branch` | string | Yes |  |
| `mirror_source_id` | integer | Yes |  |
| `priority` | integer | No |  |
| `repo_type` | [types.RepositoryType](types-RepositoryType.md) | Yes |  |
| `source_url` | string | Yes |  |
| `updated_at` | string | No |  |
| `username` | string | No | Username is the upstream Git HTTP username. |

