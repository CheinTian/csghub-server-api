# PUT /accounting/token-plans/{uuid}/update

**Resource:** [Accounting](../resources/Accounting.md)
**Update namespace token plan**
**Operation ID:** `put--accounting-token-plans-{uuid}-update`

Update the overage policy of the active namespace token plan subscription

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | namespace uuid |

## Request Body

namespace token plan update request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AcctTokenPlanUpdateNSReq](../schemas/types-AcctTokenPlanUpdateNSReq/types-AcctTokenPlanUpdateNSReq.md)

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
