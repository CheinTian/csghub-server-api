# GET /admin/compute/node/users

**Resource:** [Admin Compute Node](../resources/Admin-Compute-Node.md)
**Read /users for compute/node administration**
**Operation ID:** `get--admin-compute-node-users`

Requires compute/node administrator permission; original query parameters are preserved. Returns only id, uuid, username, nickname, and avatar.

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
