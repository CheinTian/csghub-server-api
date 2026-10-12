# GET /admin/accounting/compute_voucher/space_resources/hardware_types

**Resource:** [Admin Accounting Compute Voucher](../resources/Admin-Accounting-Compute-Voucher.md)
**Read /space_resources/hardware_types for accounting/compute_voucher administration**
**Operation ID:** `get--admin-accounting-compute_voucher-space_resources-hardware_types`

Requires accounting/compute_voucher administrator permission; original query parameters are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cluster_id` | query | string | No | Cluster ID |

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
