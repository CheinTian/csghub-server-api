# GET /admin/asset/model/models

**Resource:** [Admin Asset Model](../resources/Admin-Asset-Model.md)
**List model resources for asset administration**
**Operation ID:** `get--admin-asset-model-models`

Requires asset/model administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | search text |
| `task_tag` | query | string | No | filter by task tag, deprecated |
| `framework_tag` | query | string | No | filter by framework tag, deprecated |
| `license_tag` | query | string | No | filter by license tag, deprecated |
| `language_tag` | query | string | No | filter by language tag, deprecated |
| `tag_category` | query | string | No | filter by tag category |
| `tag_name` | query | string | No | filter by tag name |
| `tag_group` | query | string | No | filter by tag group |
| `need_op_weight` | query | boolean | No | need op weight |
| `sort` | query | string | No | sort by |
| `source` | query | enum: opencsg, huggingface, local | No | source |
| `xnet_migration_status` | query | enum: pending, running, completed... | No | filter by xnet migration status |
| `compliance_status` | query | enum: compliant, pending_review, non_compliant | No | filter by compliance status |
| `per` | query | integer | No | per |
| `page` | query | integer | No | per page |
| `model_tree` | query | string | No | example: base_model:finetune:1 |
| `list_serverless` | query | boolean | No | list serverless |
| `model_params_min` | query | number | No | minimum model parameters in billions |
| `model_params_max` | query | number | No | maximum model parameters in billions |

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
