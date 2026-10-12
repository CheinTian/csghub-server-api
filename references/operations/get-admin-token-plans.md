# GET /admin/token-plans

**Resource:** [Admin APIGateway Token Plan](../resources/Admin-APIGateway-Token-Plan.md)
**List token plans**
**Operation ID:** `get--admin-token-plans`

List token plans with optional subject type, status, period, and search filters. Requires apigateway/token_plan administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subject_type` | query | string | No | subject type |
| `status` | query | integer | No | token plan status |
| `period` | query | integer | No | billing period filter |
| `search` | query | string | No | search text |
| `per` | query | integer | No | per page |
| `page` | query | integer | No | page |

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
