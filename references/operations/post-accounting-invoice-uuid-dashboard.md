# POST /accounting/invoice/{uuid}/dashboard

**Resource:** [Accounting-Invoices](../resources/Accounting-Invoices.md)
**Get invoice dashboard data**
**Operation ID:** `post--accounting-invoice-{uuid}-dashboard`

Get invoice dashboard data, including the invoiced amount and the uninvoiced amount (paid recharge orders not invoiced yet). Amounts cover all time and are in yuan.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `Authorization` | header | string | Yes | Authorization token (Bearer <token>) |
| `uuid` | path | string | Yes | User or Org UUID |

## Request Body

Invoice Dashboard request parameters

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AccInvoiceDashboardReq](../schemas/types-AccInvoiceDashboardReq/types-AccInvoiceDashboardReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Invoice dashboard data retrieved successfully |
| 400 | Bad request format |
| 500 | Server error |

**Success Response Schema:**

[types.AccInvoiceDashboardResp](../schemas/types-AccInvoiceDashboardResp/types-AccInvoiceDashboardResp.md)

## Security

- **ApiKey**
