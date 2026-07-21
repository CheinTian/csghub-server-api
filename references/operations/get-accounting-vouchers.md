# GET /accounting/vouchers

**Resource:** [Accounting](../resources/Accounting.md)
**List vouchers**
**Operation ID:** `get--accounting-vouchers`

List vouchers with optional filters for target type, status, and search keyword. Returns paginated results.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `target_type` | query | string | No | Filter by target type (user or org) |
| `status` | query | string | No | Filter by voucher status (pending, active, expired, revoked) |
| `search` | query | string | No | Search by voucher number or target name |
| `per` | query | integer | No | Number of items per page |
| `page` | query | integer | No | Page number |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Vouchers listed successfully |
| 400 | Bad request format |
| 403 | Forbidden |
| 500 | Server error |

## Security

- **ApiKey**
