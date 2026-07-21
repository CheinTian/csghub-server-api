# PUT /admin/cluster/deploys/{id}/stop

**Resource:** [Cluster](../resources/Cluster.md)
**Admin stop a deploy by ID**
**Operation ID:** `put--admin-cluster-deploys-{id}-stop`

Administrator stops any user's deployment (space, model inference, finetune, etc.) by deploy ID, bypassing ownership checks. Also stops running workflows owned by the deploy user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | deploy ID |
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
