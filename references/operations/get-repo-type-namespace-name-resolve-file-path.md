# GET /{repo_type}/{namespace}/{name}/resolve/{file_path}

**Resource:** [Repository](../resources/Repository.md)
**Download a rep file**
**Operation ID:** `get--{repo_type}-{namespace}-{name}-resolve-{file_path}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repo_type` | path | enum: models, datasets, codes... | Yes | models,dataset,codes or spaces |
| `namespace` | path | string | Yes | repo owner name |
| `name` | path | string | Yes | repo name |
| `file_path` | path | string | Yes | file path |
| `ref` | query | string | Yes | branch or tag |
| `current_user` | query | string | No | current user name |
| `Range` | header | string | No | single byte range, for example bytes=0-1023 |
| `If-Range` | header | string | No | strong ETag used to validate a range request |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 206 | Partial Content |
| 400 | Bad request |
| 416 | Range Not Satisfiable |
| 500 | Internal server error |

## Security

- **ApiKey**
