# GET /admin/asset/space/spaces/{namespace}/{name}/size/{branch}

**Resource:** [Admin Asset Space](../resources/Admin-Asset-Space.md)
**Size space resources for asset administration**
**Operation ID:** `get--admin-asset-space-spaces-{namespace}-{name}-size-{branch}`

Requires asset/space administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | repo owner name |
| `name` | path | string | Yes | repo name |
| `branch` | path | string | Yes | branch name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
