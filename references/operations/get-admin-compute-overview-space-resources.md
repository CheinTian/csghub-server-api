# GET /admin/compute/overview/space_resources

**Resource:** [Admin Compute Overview](../resources/Admin-Compute-Overview.md)
**Read /space_resources for compute/overview administration**
**Operation ID:** `get--admin-compute-overview-space_resources`

Requires compute/overview administrator permission; original query parameters are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `per` | query | integer | No | page size |
| `page` | query | integer | No | per page |
| `cluster_id` | query | string | No | cluster_id |
| `deploy_type` | query | enum: 0, 1, 2... | No | deploy type(0-space,1-inference,2-finetune,3-serverless,4-evaluation) |
| `resource_type` | query | string | No | Resource type |
| `hardware_type` | query | string | No | Hardware type |
| `is_available` | query | boolean | No | Availability |

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
