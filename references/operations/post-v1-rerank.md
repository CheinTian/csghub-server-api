# POST /v1/rerank

**Resource:** [AIGateway](../resources/AIGateway.md)
**Rerank**
**Operation ID:** `post--v1-rerank`

Proxies rerank requests to text-ranking model endpoints (vllm / TEI / llama.cpp).

## Request Body

Rerank request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.RerankRequest](../schemas/types-RerankRequest/types-RerankRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 402 | Insufficient balance |
| 404 | Model not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

