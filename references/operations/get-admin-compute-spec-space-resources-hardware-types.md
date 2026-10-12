# GET /admin/compute/spec/space_resources/hardware_types

**Resource:** [Admin Compute Spec](../resources/Admin-Compute-Spec.md)
**Read /space_resources/hardware_types for compute/spec administration**
**Operation ID:** `get--admin-compute-spec-space_resources-hardware_types`

Requires compute/spec administrator permission; original query parameters are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cluster_id` | query | string | No | Cluster ID |

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
