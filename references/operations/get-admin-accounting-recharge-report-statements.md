# GET /admin/accounting/recharge_report/statements

**Resource:** [Admin accounting/recharge_report](../resources/Admin-accounting-recharge-report.md)
**List statements for accounting/recharge_report administration**
**Operation ID:** `get--admin-accounting-recharge_report-statements`

Requires accounting/recharge_report administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_name` | query | string | No | User name |
| `instance_name` | query | string | No | Instance name |
| `scene` | query | integer | No | Scene |
| `start_date` | query | string | Yes | Start date, format: '2024-06-12' |
| `end_date` | query | string | Yes | End date, format: '2024-06-12' |
| `per` | query | integer | No | Items per page |
| `page` | query | integer | No | Page number |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
