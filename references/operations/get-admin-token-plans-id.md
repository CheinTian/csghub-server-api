# GET /admin/token-plans/{id}

**Resource:** [Admin APIGateway Token Plan](../resources/Admin-APIGateway-Token-Plan.md)
**Get a token plan by ID**
**Operation ID:** `get--admin-token-plans-{id}`

Get the details of a token plan by its ID. Requires apigateway/token_plan administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | token plan id |

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
