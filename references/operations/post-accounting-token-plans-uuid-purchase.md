# POST /accounting/token-plans/{uuid}/purchase

**Resource:** [Accounting](../resources/Accounting.md)
**Purchase a token plan for a namespace**
**Operation ID:** `post--accounting-token-plans-{uuid}-purchase`

Purchase a token plan and create a subscription for the namespace

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | namespace uuid |

## Request Body

token plan purchase request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AcctTokenPlanPurchaseReq](../schemas/types-AcctTokenPlanPurchaseReq/types-AcctTokenPlanPurchaseReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 402 | Payment required |
| 403 | Forbidden |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
