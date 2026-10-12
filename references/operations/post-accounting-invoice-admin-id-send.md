# POST /accounting/invoice/admin/{id}/send

**Resource:** [Accounting-Invoices](../resources/Accounting-Invoices.md)
**Send invoice email to the user (admin)**
**Operation ID:** `post--accounting-invoice-admin-{id}-send`

The administrator sends the issued invoice download email to the invoice title's email address. Sending is asynchronous and best-effort.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `Authorization` | header | string | Yes | Authorization token (Bearer <token>) |
| `id` | path | integer | Yes | Invoice ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Email sent successfully |
| 400 | Bad request format |
| 401 | Authentication required |
| 403 | Invoice administration permission required |
| 404 | Invoice not found |
| 500 | Server error |

## Security

- **ApiKey**
