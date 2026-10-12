# PUT /admin/asset/code/codes/{namespace}/{name}

**Resource:** [Admin Asset Code](../resources/Admin-Asset-Code.md)
**Update code resources for asset administration**
**Operation ID:** `put--admin-asset-code-codes-{namespace}-{name}`

Requires asset/code administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateCodeReq](../schemas/types-UpdateCodeReq/types-UpdateCodeReq.md)

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
