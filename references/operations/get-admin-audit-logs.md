# GET /admin/audit_logs

**Resource:** [AuditLog](../resources/AuditLog.md)
**List audit logs**
**Operation ID:** `get--admin-audit_logs`

List audit logs with filters. Admin only.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `start_date` | query | string | No | start date (YYYY-MM-DD) |
| `end_date` | query | string | No | end date (YYYY-MM-DD) |
| `user_name` | query | string | No | user name |
| `token` | query | string | No | bearer token |
| `action` | query | string | No | audit action |
| `table_name` | query | string | No | table name |
| `auth_type` | query | string | No | auth type |
| `per` | query | integer | No | page size |
| `page` | query | integer | No | page number starts from 1 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

