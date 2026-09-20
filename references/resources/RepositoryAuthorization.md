# RepositoryAuthorization

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/{repo_type}/{namespace}/{name}/authorization/inheritance` | Get repository organization inheritance mode | [View](../operations/get-repo-type-namespace-name-authorization-inheritance.md) |
| PUT | `/{repo_type}/{namespace}/{name}/authorization/inheritance` | Set repository organization inheritance mode | [View](../operations/put-repo-type-namespace-name-authorization-inheritance.md) |
| GET | `/{repo_type}/{namespace}/{name}/authorization/organizations` | Search organizations for repository authorization | [View](../operations/get-repo-type-namespace-name-authorization-organizations.md) |
| GET | `/{repo_type}/{namespace}/{name}/authorization/users` | Search users for repository authorization | [View](../operations/get-repo-type-namespace-name-authorization-users.md) |
| GET | `/{repo_type}/{namespace}/{name}/authorizations` | List direct repository authorizations | [View](../operations/get-repo-type-namespace-name-authorizations.md) |
| POST | `/{repo_type}/{namespace}/{name}/authorizations` | Grant direct repository authorization | [View](../operations/post-repo-type-namespace-name-authorizations.md) |
| PUT | `/{repo_type}/{namespace}/{name}/authorizations/{subject_type}/{subject_id}` | Update direct repository authorization role | [View](../operations/put-repo-type-namespace-name-authorizations-subject-type-subject-id.md) |
| DELETE | `/{repo_type}/{namespace}/{name}/authorizations/{subject_type}/{subject_id}` | Remove direct repository authorization | [View](../operations/delete-repo-type-namespace-name-authorizations-subject-type-subject-id.md) |
