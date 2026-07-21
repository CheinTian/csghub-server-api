# PUT /admin/cluster/workflows/{id}/stop

**Resource:** [Cluster](../resources/Cluster.md)
**Admin stop a workflow by ID**
**Operation ID:** `put--admin-cluster-workflows-{id}-stop`

Administrator stops a running workflow by its ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | workflow ID |
| `current_user` | query | string | No | current admin user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
