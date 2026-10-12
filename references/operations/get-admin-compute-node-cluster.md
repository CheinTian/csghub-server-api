# GET /admin/compute/node/cluster

**Resource:** [Admin compute/node](../resources/Admin-compute-node.md)
**List cluster for compute/node administration**
**Operation ID:** `get--admin-compute-node-cluster`

Requires compute/node administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scope` | query | enum: all | No | Scope of cluster |

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
