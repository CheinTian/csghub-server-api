# DELETE /admin/cluster/nodes/{id}

**Resource:** [Cluster](../resources/Cluster.md)
**Delete cluster node by ID**
**Operation ID:** `delete--admin-cluster-nodes-{id}`

Delete a cluster node by its ID, along with its ownership records

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Node ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
