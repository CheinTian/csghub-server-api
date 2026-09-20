# POST /v1/embeddings

**Resource:** [AIGateway](../resources/AIGateway.md)
**Create embeddings**
**Operation ID:** `post--v1-embeddings`

Proxies embedding requests to model endpoints.

## Request Body

Embedding request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.EmbeddingRequest](../schemas/types-EmbeddingRequest/types-EmbeddingRequest.md)

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

