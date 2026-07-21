# POST /accounting/invoice/{uuid}/list

**Resource:** [Accounting-Invoices](../resources/Accounting-Invoices.md)
**List the user's invoice list**
**Operation ID:** `post--accounting-invoice-{uuid}-list`

List the invoices of a specified user based on the request parameters provided by the user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `Authorization` | header | string | Yes | Authorization token (Bearer <token>) |
| `uuid` | path | string | Yes | User or Org UUID |

## Request Body

Invoice list request parameters

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.AccInvoiceListReq](../schemas/types-AccInvoiceListReq/types-AccInvoiceListReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Invoice list retrieved successfully |
| 400 | Bad request format |
| 500 | Server error |

**Success Response Schema:**

[types.AccInvoiceListResp](../schemas/types-AccInvoiceListResp/types-AccInvoiceListResp.md)

## Security

- **ApiKey**
