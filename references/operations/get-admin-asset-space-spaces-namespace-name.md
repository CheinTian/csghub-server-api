# GET /admin/asset/space/spaces/{namespace}/{name}

**Resource:** [Admin Asset Space](../resources/Admin-Asset-Space.md)
**Show space resources for asset administration**
**Operation ID:** `get--admin-asset-space-spaces-{namespace}-{name}`

Requires asset/space administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `need_op_weight` | query | boolean | No | need op weight |

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
