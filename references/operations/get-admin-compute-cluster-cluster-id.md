# GET /admin/compute/cluster/cluster/{id}

**Resource:** [Admin Compute Cluster](../resources/Admin-Compute-Cluster.md)
**Read /cluster/:id for compute/cluster administration**
**Operation ID:** `get--admin-compute-cluster-cluster-{id}`

Requires compute/cluster administrator permission; original query parameters are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Id |

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
