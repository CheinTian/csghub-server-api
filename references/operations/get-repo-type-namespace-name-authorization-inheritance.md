# GET /{repo_type}/{namespace}/{name}/authorization/inheritance

**Resource:** [RepositoryAuthorization](../resources/RepositoryAuthorization.md)
**Get repository organization inheritance mode**
**Operation ID:** `get--{repo_type}-{namespace}-{name}-authorization-inheritance`

Returns valid=false and blocked=false when the repository is not in a hierarchical organization namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repo_type` | path | enum: models, datasets, codes... | Yes | Repository type |
| `namespace` | path | string | Yes | Repository namespace |
| `name` | path | string | Yes | Repository name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

## Security

- **ApiKey**
