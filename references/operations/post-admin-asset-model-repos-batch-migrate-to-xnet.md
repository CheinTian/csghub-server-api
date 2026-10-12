# POST /admin/asset/model/repos/batch_migrate_to_xnet

**Resource:** [Admin Asset Model](../resources/Admin-Asset-Model.md)
**Batch migrate model repositories to Xnet**
**Operation ID:** `post--admin-asset-model-repos-batch_migrate_to_xnet`

Requires asset/model administrator permission. Only model repositories are selected; request parameters cannot change the repository type.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
