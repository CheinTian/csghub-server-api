# PUT /config/upstreams/{id}

**Resource:** [LLMService](../resources/LLMService.md)
**Update Upstream**
**Operation ID:** `put--config-upstreams-{id}`

Update an existing upstream endpoint by ID. Only non-nil fields will be updated.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | upstream ID |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateUpstreamReq](../schemas/types-UpdateUpstreamReq/types-UpdateUpstreamReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

