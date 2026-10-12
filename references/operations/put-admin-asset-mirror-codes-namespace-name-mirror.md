# PUT /admin/asset/mirror/codes/{namespace}/{name}/mirror

**Resource:** [Admin Asset Mirror](../resources/Admin-Asset-Mirror.md)
**Update mirror configuration for administration**
**Operation ID:** `put--admin-asset-mirror-codes-{namespace}-{name}-mirror`

Requires asset/mirror permission. Source validation and shared business constraints are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | Repository owner name |
| `name` | path | string | Yes | Repository name |

## Request Body

Mirror operation parameters

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateMirrorParams](../schemas/types-UpdateMirrorParams/types-UpdateMirrorParams.md)

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
