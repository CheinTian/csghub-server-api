# DELETE /internal/agent/templates/{id}

**Resource:** [Agent](../resources/Agent.md)
**Delete an internal agent template**
**Operation ID:** `delete--internal-agent-templates-{id}`

Permanently delete an internal agent template owned by the system user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | Template ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 404 | Not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
