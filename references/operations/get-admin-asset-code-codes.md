# GET /admin/asset/code/codes

**Resource:** [Admin Asset Code](../resources/Admin-Asset-Code.md)
**List code resources for asset administration**
**Operation ID:** `get--admin-asset-code-codes`

Requires asset/code administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | search text |
| `task_tag` | query | string | No | filter by task tag |
| `framework_tag` | query | string | No | filter by framework tag |
| `license_tag` | query | string | No | filter by license tag |
| `language_tag` | query | string | No | filter by language tag |
| `need_op_weight` | query | boolean | No | need op weight |
| `sort` | query | string | No | sort by |
| `source` | query | enum: opencsg, huggingface, local | No | source |
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
