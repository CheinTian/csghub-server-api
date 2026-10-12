# GET /admin/compute/node/space_resources/hardware_types

**Resource:** [Admin compute/node](../resources/Admin-compute-node.md)
**List space_resources/hardware_types for compute/node administration**
**Operation ID:** `get--admin-compute-node-space_resources-hardware_types`

Requires compute/node administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cluster_id` | query | string | No | cluster_id |

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
