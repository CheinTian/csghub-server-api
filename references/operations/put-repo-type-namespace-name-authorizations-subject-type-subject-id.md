# PUT /{repo_type}/{namespace}/{name}/authorizations/{subject_type}/{subject_id}

**Resource:** [RepositoryAuthorization](../resources/RepositoryAuthorization.md)
**Update direct repository authorization role**
**Operation ID:** `put--{repo_type}-{namespace}-{name}-authorizations-{subject_type}-{subject_id}`

Updates an existing direct grant; submitting the current role is idempotent.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repo_type` | path | enum: models, datasets, codes... | Yes | Repository type |
| `namespace` | path | string | Yes | Repository namespace |
| `name` | path | string | Yes | Repository name |
| `subject_type` | path | enum: user, organization | Yes | Subject type |
| `subject_id` | path | integer | Yes | Subject ID |

## Request Body

Authorization role

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.RepositoryAuthorizationRoleRequest](../schemas/types-RepositoryAuthorizationRoleRequest/types-RepositoryAuthorizationRoleRequest.md)

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
