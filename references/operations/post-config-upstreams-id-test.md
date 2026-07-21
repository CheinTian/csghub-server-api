# POST /config/upstreams/{id}/test

**Resource:** [LLMService](../resources/LLMService.md)
**Test Upstream Connection**
**Operation ID:** `post--config-upstreams-{id}-test`

Test connectivity to an upstream endpoint by ID. The backend fetches the upstream config from the database, sends a simple "hi" prompt to the upstream URL (supporting /chat/completions and /responses endpoints), and returns the masked request summary, response status, body and content. This avoids CORS issues when testing upstream endpoints from the frontend.

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

