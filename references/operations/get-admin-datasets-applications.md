# GET /admin/datasets/applications

**Resource:** [Dataset](../resources/Dataset.md)
**List dataset applications**
**Operation ID:** `get--admin-datasets-applications`

list dataset applications, optionally filtered by status and search by dataset name or path

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `current_user` | query | string | No | current user |
| `status` | query | enum: pending, approved, rejected | No | filter by status |
| `search` | query | string | No | search by dataset name or path |
| `per` | query | integer | No | per |
| `page` | query | integer | No | per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
