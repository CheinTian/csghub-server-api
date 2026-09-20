# GET /accounting/token-report/export

**Resource:** [Accounting](../resources/Accounting.md)
**Export token operations report as CSV (streaming)**
**Operation ID:** `get--accounting-token-report-export`

Export the token operations report (issue #3404) as CSV with streaming output; the last row is the totals (合计) row. Money columns are yuan.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_name` | query | string | No | User or org name (namespace path) |
| `ns_uuid` | query | string | No | Namespace uuid |
| `resource_id` | query | string | No | Model resource id |
| `provider` | query | string | No | Provider (服务商) |
| `token_id` | query | integer | No | Access token id |
| `start_date` | query | string | No | Start date, format: '2026-08-01'; defaults to current month |
| `end_date` | query | string | No | End date, format: '2026-08-31'; defaults to current month |

## Responses

| Status | Description |
|--------|-------------|
| 200 | CSV file download |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
