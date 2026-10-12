# PUT /accounting/token-plans/{uuid}/cancel

**Resource:** [Accounting](../resources/Accounting.md)
**Cancel token plan for a namespace**
**Operation ID:** `put--accounting-token-plans-{uuid}-cancel`

Cancel automatic renewal of the namespace token plan subscription

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | namespace uuid |

## Request Body

token plan cancel request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AcctTokenPlanCancelReq](../schemas/types-AcctTokenPlanCancelReq/types-AcctTokenPlanCancelReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 404 | Not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
