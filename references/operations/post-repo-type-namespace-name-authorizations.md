# POST /{repo_type}/{namespace}/{name}/authorizations

**Resource:** [RepositoryAuthorization](../resources/RepositoryAuthorization.md)
**Grant direct repository authorization**
**Operation ID:** `post--{repo_type}-{namespace}-{name}-authorizations`

Creates or updates a direct read or write grant for one user or organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repo_type` | path | enum: models, datasets, codes... | Yes | Repository type |
| `namespace` | path | string | Yes | Repository namespace |
| `name` | path | string | Yes | Repository name |

## Request Body

Authorization subject and role

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.RepositoryAuthorizationRequest](../schemas/types-RepositoryAuthorizationRequest/types-RepositoryAuthorizationRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
