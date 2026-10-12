# GET /admin/compute/overview/cluster/workflows

**Resource:** [Admin Compute Overview](../resources/Admin-Compute-Overview.md)
**Read /admin/cluster/workflows for compute/overview administration**
**Operation ID:** `get--admin-compute-overview-cluster-workflows`

Requires compute/overview administrator permission; original query parameters are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cluster_id` | query | string | No | cluster id |
| `cluster_node` | query | string | No | cluster node |
| `status` | query | string | No | status |
| `resource_id` | query | integer | No | resource id |
| `search` | query | string | No | search keyword |
| `per` | query | integer | No | per page |
| `page` | query | integer | No | page |
| `start_time` | query | string | No | start time (e.g., 2024-01-01 or 2024-01-01 00:00:00) |
| `end_time` | query | string | No | end time (e.g., 2024-01-31 or 2024-01-31 23:59:59) |

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
