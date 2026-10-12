# GET /admin/asset/code/codes/{namespace}/{name}

**Resource:** [Admin Asset Code](../resources/Admin-Asset-Code.md)
**Show code resources for asset administration**
**Operation ID:** `get--admin-asset-code-codes-{namespace}-{name}`

Requires asset/code administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `need_op_weight` | query | boolean | No | need op weight |
| `need_multi_sync` | query | boolean | No | need multi sync |

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
