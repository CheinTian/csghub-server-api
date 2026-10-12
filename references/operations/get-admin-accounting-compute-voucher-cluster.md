# GET /admin/accounting/compute_voucher/cluster

**Resource:** [Admin Accounting Compute Voucher](../resources/Admin-Accounting-Compute-Voucher.md)
**Read /cluster for accounting/compute_voucher administration**
**Operation ID:** `get--admin-accounting-compute_voucher-cluster`

Requires accounting/compute_voucher administrator permission; original query parameters are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scope` | query | enum: all | No | Scope of cluster |

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
