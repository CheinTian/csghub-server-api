# DELETE /config/upstreams/{id}

**Resource:** [LLMService](../resources/LLMService.md)
**Delete Upstream**
**Operation ID:** `delete--config-upstreams-{id}`

Delete an upstream endpoint by ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | upstream ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

