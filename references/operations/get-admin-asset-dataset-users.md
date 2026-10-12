# GET /admin/asset/dataset/users

**Resource:** [Admin Asset Dataset](../resources/Admin-Asset-Dataset.md)
**Read /users for asset/dataset administration**
**Operation ID:** `get--admin-asset-dataset-users`

Requires asset/dataset administrator permission; original query parameters are preserved. Returns only id, uuid, username, nickname, and avatar.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |
| `search` | query | string | No | Search text |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
