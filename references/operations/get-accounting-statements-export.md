# GET /accounting/statements/export

**Resource:** [Accounting](../resources/Accounting.md)
**Export all statements as CSV (streaming)**
**Operation ID:** `get--accounting-statements-export`

Export all statements (no pagination limit) by user name, instance name, scene and time range. Returns a CSV file with streaming output.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_name` | query | string | No | User name |
| `instance_name` | query | string | No | Instance name |
| `scene` | query | integer | No | Scene |
| `start_date` | query | string | Yes | Start date, format: '2024-06-12' |
| `end_date` | query | string | Yes | End date, format: '2024-06-12' |

## Responses

| Status | Description |
|--------|-------------|
| 200 | CSV file download |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
