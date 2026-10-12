# GET /admin/compute/node/cluster/nodes

**Resource:** [Admin Compute Node](../resources/Admin-Compute-Node.md)
**Read /admin/cluster/nodes for compute/node administration**
**Operation ID:** `get--admin-compute-node-cluster-nodes`

Requires compute/node administrator permission; original query parameters are preserved.

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
