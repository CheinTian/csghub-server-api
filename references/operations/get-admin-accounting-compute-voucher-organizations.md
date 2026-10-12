# GET /admin/accounting/compute_voucher/organizations

**Resource:** [Admin Accounting Compute Voucher](../resources/Admin-Accounting-Compute-Voucher.md)
**Read /organizations for compute voucher and token plan administration**
**Operation ID:** `get--admin-accounting-compute_voucher-organizations`

Requires accounting/compute_voucher or apigateway/token_plan administrator permission; original query parameters are preserved. Only selector identity, display fields, and namespace identifiers are returned; contact details, roles, verification metadata, and tags are excluded.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |
| `search` | query | string | No | Search text |
| `org_type` | query | string | No | Organization type filter |
| `verify_status` | query | string | No | Verification status filter |
| `tag` | query | string | No | Tag name filter |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

## Security

- **ApiKey**
