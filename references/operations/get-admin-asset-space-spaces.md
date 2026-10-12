# GET /admin/asset/space/spaces

**Resource:** [Admin Asset Space](../resources/Admin-Asset-Space.md)
**List space resources for asset administration**
**Operation ID:** `get--admin-asset-space-spaces`

Requires asset/space administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | search text |
| `task_tag` | query | string | No | filter by task tag |
| `framework_tag` | query | string | No | filter by framework tag |
| `license_tag` | query | string | No | filter by license tag |
| `language_tag` | query | string | No | filter by language tag |
| `sort` | query | string | No | sort by |
| `source` | query | enum: opencsg, huggingface, local | No | source |
| `sdk` | query | string | No | filter by space sdk |
| `status` | query | enum: Building, BuildingFailed, Deploying... | No | filter by space status |
| `per` | query | integer | No | per |
| `page` | query | integer | No | per page |

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
