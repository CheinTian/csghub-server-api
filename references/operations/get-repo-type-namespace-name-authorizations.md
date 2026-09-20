# GET /{repo_type}/{namespace}/{name}/authorizations

**Resource:** [RepositoryAuthorization](../resources/RepositoryAuthorization.md)
**List direct repository authorizations**
**Operation ID:** `get--{repo_type}-{namespace}-{name}-authorizations`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repo_type` | path | enum: models, datasets, codes... | Yes | Repository type |
| `namespace` | path | string | Yes | Repository namespace |
| `name` | path | string | Yes | Repository name |
| `page` | query | integer | No | Page number |
| `page_size` | query | integer | No | Page size |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

## Security

- **ApiKey**
