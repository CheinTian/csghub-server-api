# POST /finetuneV2

**Resource:** [Finetune](../resources/Finetune.md)
**run finetune with CPU transfer stages**
**Operation ID:** `post--finetuneV2`

## Request Body

body setting of finetune

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.FinetuneReq](../schemas/types-FinetuneReq/types-FinetuneReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[types.ArgoWorkFlowRes](../schemas/types-ArgoWorkFlowRes/types-ArgoWorkFlowRes.md)

## Security

- **ApiKey**
