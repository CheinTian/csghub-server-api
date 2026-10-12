# GET /admin/asset/model/users

**Resource:** [Admin Asset Model](../resources/Admin-Asset-Model.md)
**Read /users for asset/model administration**
**Operation ID:** `get--admin-asset-model-users`

Requires asset/model administrator permission; original query parameters are preserved. Returns only id, uuid, username, nickname, and avatar.

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
