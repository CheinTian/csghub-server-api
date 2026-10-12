# GET /admin/accounting/compute_voucher/users

**Resource:** [Admin Accounting Compute Voucher](../resources/Admin-Accounting-Compute-Voucher.md)
**Read /users for compute voucher and token plan administration**
**Operation ID:** `get--admin-accounting-compute_voucher-users`

Requires accounting/compute_voucher or apigateway/token_plan administrator permission; original query parameters are preserved. Returns only id, uuid, username, nickname, and avatar.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |
| `search` | query | string | No | Search text |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
