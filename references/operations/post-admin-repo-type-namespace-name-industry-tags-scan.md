# POST /admin/{repo_type}/{namespace}/{name}/industry_tags/scan

**Resource:** [Repository](../resources/Repository.md)
**Trigger repository industry tag scan**
**Operation ID:** `post--admin-{repo_type}-{namespace}-{name}-industry_tags-scan`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repo_type` | path | enum: dataset, model | Yes | repo type |
| `namespace` | path | string | Yes | repo owner name |
| `name` | path | string | Yes | repo name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
