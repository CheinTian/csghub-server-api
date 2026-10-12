# GET /admin/asset/dataset/datasets

**Resource:** [Admin Asset Dataset](../resources/Admin-Asset-Dataset.md)
**List dataset resources for asset administration**
**Operation ID:** `get--admin-asset-dataset-datasets`

Requires asset/dataset administrator permission.

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
| `xnet_migration_status` | query | enum: pending, running, completed... | No | filter by xnet migration status |
| `compliance_status` | query | enum: compliant, pending_review, non_compliant | No | filter by compliance status |
| `dataset_type` | query | enum: commercial, normal | No | filter by dataset type |
| `user_purchased` | query | boolean | No | filter by user purchased |
| `repo_size_min` | query | integer | No | minimum repository size in bytes |
| `repo_size_max` | query | integer | No | maximum repository size in bytes |
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
