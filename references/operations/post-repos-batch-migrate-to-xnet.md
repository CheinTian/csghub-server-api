# POST /repos/batch_migrate_to_xnet

**Resource:** [Repository](../resources/Repository.md)
**Batch migrate all repos to Xnet**
**Operation ID:** `post--repos-batch_migrate_to_xnet`

Requires global (*) administrator permission to start the batch migration of all repository types.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
