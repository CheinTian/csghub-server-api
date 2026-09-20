# PUT /{repo_type}/{namespace}/{name}/authorization/inheritance

**Resource:** [RepositoryAuthorization](../resources/RepositoryAuthorization.md)
**Set repository organization inheritance mode**
**Operation ID:** `put--{repo_type}-{namespace}-{name}-authorization-inheritance`

This setting is applicable only to repositories in hierarchical organization namespaces.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repo_type` | path | enum: models, datasets, codes... | Yes | Repository type |
| `namespace` | path | string | Yes | Repository namespace |
| `name` | path | string | Yes | Repository name |

## Request Body

Inheritance mode

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.RepositoryInheritanceRequest](../schemas/types-RepositoryInheritanceRequest/types-RepositoryInheritanceRequest.md)

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
