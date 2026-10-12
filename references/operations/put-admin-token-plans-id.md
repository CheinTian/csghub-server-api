# PUT /admin/token-plans/{id}

**Resource:** [Admin APIGateway Token Plan](../resources/Admin-APIGateway-Token-Plan.md)
**Update a token plan**
**Operation ID:** `put--admin-token-plans-{id}`

Partially update an existing token plan by its ID. Requires apigateway/token_plan administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | token plan id |

## Request Body

token plan update request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AcctTokenPlanUpdateReq](../schemas/types-AcctTokenPlanUpdateReq/types-AcctTokenPlanUpdateReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
