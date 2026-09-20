# GET /accounting/metering/{id}/summary

**Resource:** [Accounting](../resources/Accounting.md)
**Query statistics summary by user uuid and date range**
**Operation ID:** `get--accounting-metering-{id}-summary`

Query statistics summary grouped by scene for a user within a date range

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | user uuid |
| `scene` | query | enum: 10, 11, 12... | No | scene |
| `start_date` | query | string | Yes | start_date, format: '2024-06-12' |
| `end_date` | query | string | Yes | end_date, format: '2024-06-12' |
| `current_user` | query | string | Yes | current_user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
