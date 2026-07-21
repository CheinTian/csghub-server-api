# PUT /api/v1/inference-arch

**Resource:** [inference-arch](../resources/inference-arch.md)
**Update inference arch configuration**
**Operation ID:** `put--api-v1-inference-arch`

Update the inference arch configuration (only one record allowed)

## Request Body

Update inference arch request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateInferenceArchReq](../schemas/types-CreateInferenceArchReq/types-CreateInferenceArchReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[types.InferenceArch](../schemas/types-InferenceArch/types-InferenceArch.md)

