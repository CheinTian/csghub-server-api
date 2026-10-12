# GET /admin/asset/mirror/skills/{namespace}/{name}/mirror/progress

**Resource:** [Admin Asset Mirror](../resources/Admin-Asset-Mirror.md)
**Get repository mirror progress for administration**
**Operation ID:** `get--admin-asset-mirror-skills-{namespace}-{name}-mirror-progress`

Requires asset/mirror permission. Existing progress reporting behavior is preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | Repository owner name |
| `name` | path | string | Yes | Repository name |

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
