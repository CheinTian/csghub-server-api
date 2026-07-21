# GET /accounting/credit/portal-recharges

**Resource:** [Accounting](../resources/Accounting.md)
**Query portal recharges (non-cash recharges)**
**Operation ID:** `get--accounting-credit-portal-recharges`

Query portal recharge records (scene=1) by user UUID and time range

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_uuid` | query | string | No | User UUID, empty for all users |
| `start_date` | query | string | Yes | Start date (format: '2024-06-12') |
| `end_date` | query | string | Yes | End date (format: '2024-06-12') |
| `per` | query | integer | No | Results per page |
| `page` | query | integer | No | Page number |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully fetched portal recharge data |
| 400 | Bad request, invalid parameters |
| 500 | Internal server error |

**Success Response Schema:**

[types.AcctRechargeListResp](../schemas/types-AcctRechargeListResp/types-AcctRechargeListResp.md)

## Security

- **ApiKey**
