# GET /admin/accounting/compute_voucher/user/{username}

**Resource:** [Admin Accounting Compute Voucher](../resources/Admin-Accounting-Compute-Voucher.md)
**Read /user/:username for compute voucher and token plan administration**
**Operation ID:** `get--admin-accounting-compute_voucher-user-{username}`

Requires accounting/compute_voucher or apigateway/token_plan administrator permission; original query parameters are preserved. Only selector identity, display fields, and namespace identifiers are returned; contact details, roles, verification metadata, and tags are excluded.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | path | string | Yes | Username |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
