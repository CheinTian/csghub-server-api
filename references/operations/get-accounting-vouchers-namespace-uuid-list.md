# GET /accounting/vouchers/namespace/{uuid}/list

**Resource:** [Accounting](../resources/Accounting.md)
**List vouchers for a namespace**
**Operation ID:** `get--accounting-vouchers-namespace-{uuid}-list`

List vouchers for a user or organization namespace UUID, with optional status filter and pagination. Only the namespace owner or admin can query.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | User or Org UUID |
| `status` | query | string | No | Filter by voucher status (pending, active, expired, revoked) |
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
