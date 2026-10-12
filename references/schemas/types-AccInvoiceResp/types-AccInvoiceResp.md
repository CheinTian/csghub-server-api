# types.AccInvoiceResp

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `apply_time` | string | No | Invoice application time |
| `bank_account` | string | No | Bank account number |
| `bank_name` | string | No | Bank name |
| `bill_cycle` | string | No | Billing cycle |
| `contact_phone` | string | No | Contact phone number |
| `created_at` | string | No | Creation time |
| `email` | string | No | Email address |
| `email_send_status` | string | No | EmailSendStatus is none/sent/failed; EmailSentAt is the timestamp of the
last successful send, null when no email has been sent yet. |
| `email_sent_at` | string | No |  |
| `id` | integer | No |  |
| `invoice_amount` | number | No | Invoice amount |
| `invoice_date` | string | No | Invoice issuance date |
| `invoice_title` | string | No | Invoice title |
| `invoice_type` | string | No | Invoice type |
| `invoice_url` | string | No | Invoice URL |
| `reason` | string | No | Reason |
| `recharge_orders` | types.AccInvoiceRechargeOrder[] | No | Recharge orders invoiced together. Empty for legacy bill-cycle invoices
(bill_cycle is non-empty there) and populated for recharge-based invoices. |
| `registered_addr` | string | No | Registered address |
| `status` | string | No | Invoice status eq processing,issued,failed |
| `taxpayer_id` | string | No | Taxpayer identification number |
| `title_type` | string | No | Invoice title type |
| `updated_at` | string | No | Update time |
| `user_name` | string | No | User name |
| `user_uuid` | string | No |  |

