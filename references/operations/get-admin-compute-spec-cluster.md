# GET /admin/compute/spec/cluster

**Resource:** [Admin Compute Spec](../resources/Admin-Compute-Spec.md)
**Read /cluster for compute/spec administration**
**Operation ID:** `get--admin-compute-spec-cluster`

Requires compute/spec administrator permission; original query parameters are preserved.

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
