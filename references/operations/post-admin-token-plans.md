# POST /admin/token-plans

**Resource:** [Admin APIGateway Token Plan](../resources/Admin-APIGateway-Token-Plan.md)
**Create a token plan**
**Operation ID:** `post--admin-token-plans`

Create a token plan for later purchase by namespaces. Requires apigateway/token_plan administrator permission.

## Request Body

token plan create request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AcctTokenPlanCreateReq](../schemas/types-AcctTokenPlanCreateReq/types-AcctTokenPlanCreateReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
