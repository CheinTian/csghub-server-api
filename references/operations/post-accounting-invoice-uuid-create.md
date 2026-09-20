# POST /accounting/invoice/{uuid}/create

**Resource:** [Accounting-Invoices](../resources/Accounting-Invoices.md)
**Create a new invoice**
**Operation ID:** `post--accounting-invoice-{uuid}-create`

Create a new invoice for the selected paid recharge orders. The invoice amount is computed from the orders server-side.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `Authorization` | header | string | Yes | Authorization token (Bearer <token>) |
| `uuid` | path | string | Yes | User or Org UUID |

## Request Body

Invoice creation request parameters

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AccInvoiceCreateReq](../schemas/types-AccInvoiceCreateReq/types-AccInvoiceCreateReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Invoice created successfully |
| 400 | Bad request format |
| 500 | Server error |

## Security

- **ApiKey**
