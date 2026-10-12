# PUT /accounting/credit/{id}/recharge

**Resource:** [Accounting](../resources/Accounting.md)
**Recharge an active user's account**
**Operation ID:** `put--accounting-credit-{id}-recharge`

Requires account/user permission and an active personal user UUID; organization targets are rejected with 403. The authenticated operator overrides client identity fields.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Active personal user UUID |

## Request Body

Recharge amount, scene, purpose and optional purpose description; op_uid is ignored

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.RechargeReq](../schemas/types-RechargeReq/types-RechargeReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden target or insufficient permission |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
