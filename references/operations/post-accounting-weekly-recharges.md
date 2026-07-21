# POST /accounting/weekly_recharges

**Resource:** [Accounting](../resources/Accounting.md)
**Send weekly recharges report**
**Operation ID:** `post--accounting-weekly_recharges`

Generate and send the weekly recharges report to specified email recipients.

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.WeeklyRechargesReq](../schemas/types-WeeklyRechargesReq/types-WeeklyRechargesReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
