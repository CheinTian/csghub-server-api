# POST /v1/systemone

**Resource:** [AIGateway](../resources/AIGateway.md)
**Jev System One API**
**Operation ID:** `post--v1-systemone`

Evaluate a state against a set of typed questions using a Jev (System One) model, following the TypeSafe SDK protocol. Requests are routed through the shared three-phase pipeline (Extract → Plan → Execute) with upstream authentication, timeout handling, LLM generation tracing, and LLM training log capture.

## Request Body

Jev System One request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.JevRequest](../schemas/types-JevRequest/types-JevRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 402 | Payment Required |
| 404 | Not Found |
| 429 | Too Many Requests |
| 500 | Internal Server Error |
| 504 | Gateway Timeout |

**Success Response Schema:**

[types.JevResponse](../schemas/types-JevResponse/types-JevResponse.md)

