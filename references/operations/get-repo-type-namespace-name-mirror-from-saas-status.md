# GET /{repo_type}/{namespace}/{name}/mirror_from_saas/status

**Resource:** [Repository](../resources/Repository.md)
**Get the current OpenCSG SaaS mirror synchronization status**
**Operation ID:** `get--{repo_type}-{namespace}-{name}-mirror_from_saas-status`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repo_type` | path | string | Yes | models,datasets,codes,spaces,prompts,mcp or skills |
| `namespace` | path | string | Yes | repo owner name |
| `name` | path | string | Yes | repo name |
| `task_id` | query | integer | No | task observed by the caller |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 500 | Internal server error |

## Security

- **ApiKey**
