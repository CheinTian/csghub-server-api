# GET /accounting/token-report

**Resource:** [Accounting](../resources/Accounting.md)
**Token operations report: daily rows by namespace, API key, model and provider**
**Operation ID:** `get--accounting-token-report`

Token operations report (issue #3404): daily rows by namespace, API key, model and provider with calls, tokens, cache hit rate, revenue, cost and margin, plus a totals row. Data is T+1 (nightly rollup).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_name` | query | string | No | User or org name (namespace path) |
| `ns_uuid` | query | string | No | Namespace uuid |
| `resource_id` | query | string | No | Model resource id, e.g. thirdparty://deepseek-r1 |
| `provider` | query | string | No | Provider (服务商) |
| `token_id` | query | integer | No | Access token id |
| `start_date` | query | string | No | Start date, format: '2026-08-01'; defaults to current month |
| `end_date` | query | string | No | End date, format: '2026-08-31'; defaults to current month |
| `per` | query | integer | No | Items per page |
| `page` | query | integer | No | Page number |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
