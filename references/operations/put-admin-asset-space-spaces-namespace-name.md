# PUT /admin/asset/space/spaces/{namespace}/{name}

**Resource:** [Admin Asset Space](../resources/Admin-Asset-Space.md)
**Update space resources for asset administration**
**Operation ID:** `put--admin-asset-space-spaces-{namespace}-{name}`

Requires asset/space administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateSpaceReq](../schemas/types-UpdateSpaceReq/types-UpdateSpaceReq.md)

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
