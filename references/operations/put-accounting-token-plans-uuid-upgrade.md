# PUT /accounting/token-plans/{uuid}/upgrade

**Resource:** [Accounting](../resources/Accounting.md)
**Upgrade token plan for a namespace**
**Operation ID:** `put--accounting-token-plans-{uuid}-upgrade`

Upgrade the namespace token plan subscription to another token plan

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | namespace uuid |

## Request Body

token plan upgrade request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AcctTokenPlanUpgradeReq](../schemas/types-AcctTokenPlanUpgradeReq/types-AcctTokenPlanUpgradeReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 402 | Payment required |
| 403 | Forbidden |
| 404 | Not found |
| 409 | Token plan already in use |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
