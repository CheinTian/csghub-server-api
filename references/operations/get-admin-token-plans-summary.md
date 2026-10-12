# GET /admin/token-plans/summary

**Resource:** [Admin APIGateway Token Plan](../resources/Admin-APIGateway-Token-Plan.md)
**Summarize token plans**
**Operation ID:** `get--admin-token-plans-summary`

Get token plan summary counts for the admin dashboard. Requires apigateway/token_plan administrator permission.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
