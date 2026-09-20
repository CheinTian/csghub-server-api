# GET /{repo_type}/{namespace}/{name}/authorization/users

**Resource:** [RepositoryAuthorization](../resources/RepositoryAuthorization.md)
**Search users for repository authorization**
**Operation ID:** `get--{repo_type}-{namespace}-{name}-authorization-users`

Returns each user's highest effective repository role together with whether a manageable direct user grant exists.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repo_type` | path | enum: models, datasets, codes... | Yes | Repository type |
| `namespace` | path | string | Yes | Repository namespace |
| `name` | path | string | Yes | Repository name |
| `keyword` | query | string | No | User name, username, or email |
| `limit` | query | integer | No | Maximum number of results |

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
