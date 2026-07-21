# POST /config/upstreams

**Resource:** [LLMService](../resources/LLMService.md)
**Create Upstream**
**Operation ID:** `post--config-upstreams`

Add a new upstream endpoint to an existing LLM config.

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateUpstreamReq](../schemas/types-CreateUpstreamReq/types-CreateUpstreamReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

