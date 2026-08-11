# Accounting

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounting/credit/balance` | Get all users balance | [View](../operations/get-accounting-credit-balance.md) |
| PUT | `/accounting/credit/low-balance-warn` | Set low balance warning threshold | [View](../operations/put-accounting-credit-low-balance-warn.md) |
| GET | `/accounting/credit/portal-recharges` | Query portal recharges (non-cash recharges) | [View](../operations/get-accounting-credit-portal-recharges.md) |
| GET | `/accounting/credit/{id}/balance` | Get user balance by user uuid | [View](../operations/get-accounting-credit-id-balance.md) |
| GET | `/accounting/credit/{id}/bills` | List user bills by user uuid and start date and end date | [View](../operations/get-accounting-credit-id-bills.md) |
| GET | `/accounting/credit/{id}/bills/instance` | List user bills detail by user uuid, instance name, start date and end date | [View](../operations/get-accounting-credit-id-bills-instance.md) |
| PUT | `/accounting/credit/{id}/recharge` | Recharge fee for account | [View](../operations/put-accounting-credit-id-recharge.md) |
| GET | `/accounting/credit/{id}/recharge/list` | List recharges by user or org uuid and start time and end time | [View](../operations/get-accounting-credit-id-recharge-list.md) |
| GET | `/accounting/credit/{id}/statements` | List statements by user uuid and start time and end time | [View](../operations/get-accounting-credit-id-statements.md) |
| GET | `/accounting/metering/{id}/statements` | List meterings by user uuid and start time and end time | [View](../operations/get-accounting-metering-id-statements.md) |
| GET | `/accounting/multisync/download` | Get account quota statement | [View](../operations/get-accounting-multisync-download.md) |
| POST | `/accounting/multisync/downloads` | Add download count | [View](../operations/post-accounting-multisync-downloads.md) |
| GET | `/accounting/multisync/quota` | Get account quota by user id | [View](../operations/get-accounting-multisync-quota.md) |
| POST | `/accounting/multisync/quotas` | Add or update account quota | [View](../operations/post-accounting-multisync-quotas.md) |
| GET | `/accounting/present` | List non-cash recharges by user name, user uuid and time range | [View](../operations/get-accounting-present.md) |
| GET | `/accounting/presents` | List non-cash recharges by user UUID, time range and pagination | [View](../operations/get-accounting-presents.md) |
| GET | `/accounting/price` | List sku prices | [View](../operations/get-accounting-price.md) |
| POST | `/accounting/price` | Add sku price | [View](../operations/post-accounting-price.md) |
| POST | `/accounting/price/batch` | Batch create sku prices | [View](../operations/post-accounting-price-batch.md) |
| GET | `/accounting/price/distinct` | Query distinct prices | [View](../operations/get-accounting-price-distinct.md) |
| GET | `/accounting/price/multi-kind` | List sku prices by multiple sku kinds | [View](../operations/get-accounting-price-multi-kind.md) |
| GET | `/accounting/price/{id}` | Get price by id | [View](../operations/get-accounting-price-id.md) |
| PUT | `/accounting/price/{id}` | Update sku price | [View](../operations/put-accounting-price-id.md) |
| DELETE | `/accounting/price/{id}` | Delete price by id | [View](../operations/delete-accounting-price-id.md) |
| GET | `/accounting/recharge/list` | List recharges by user name, order no, status, payment type and time range | [View](../operations/get-accounting-recharge-list.md) |
| POST | `/accounting/recharge/{uuid}/create-pay-order` | Create recharge order for user or org | [View](../operations/post-accounting-recharge-uuid-create-pay-order.md) |
| GET | `/accounting/recharge/{uuid}/list` | List current user recharge list by start_time and end_time and query | [View](../operations/get-accounting-recharge-uuid-list.md) |
| GET | `/accounting/recharge/{uuid}/status` | Fetch recharge order status by recharge id | [View](../operations/get-accounting-recharge-uuid-status.md) |
| GET | `/accounting/recharges` | List recharges by user name, order no, status, payment type and time range | [View](../operations/get-accounting-recharges.md) |
| GET | `/accounting/statements` | List statements by user name, instance name, scene and time range | [View](../operations/get-accounting-statements.md) |
| GET | `/accounting/statements/export` | Export all statements as CSV (streaming) | [View](../operations/get-accounting-statements-export.md) |
| GET | `/accounting/stripe/pay/cancel` | Mark stripe pay session as cancel | [View](../operations/get-accounting-stripe-pay-cancel.md) |
| GET | `/accounting/stripe/pay/sessions` | List pay sessions by user uuid and start time and end time | [View](../operations/get-accounting-stripe-pay-sessions.md) |
| GET | `/accounting/stripe/pay/sessions/{id}` | Get a stripe pay session | [View](../operations/get-accounting-stripe-pay-sessions-id.md) |
| DELETE | `/accounting/stripe/pay/sessions/{id}` | Close a stripe pay session | [View](../operations/delete-accounting-stripe-pay-sessions-id.md) |
| GET | `/accounting/stripe/pay/success` | Mark stripe pay session as success | [View](../operations/get-accounting-stripe-pay-success.md) |
| POST | `/accounting/stripe/pay/{uuid}/sessions` | Create stripe pay session | [View](../operations/post-accounting-stripe-pay-uuid-sessions.md) |
| GET | `/accounting/subscriptions` | List subscriptions by user uuid and start time and end time | [View](../operations/get-accounting-subscriptions.md) |
| POST | `/accounting/subscriptions` | Post a subscription change for a user | [View](../operations/post-accounting-subscriptions.md) |
| GET | `/accounting/subscriptions/bills` | List bills by user uuid and start time and end time | [View](../operations/get-accounting-subscriptions-bills.md) |
| GET | `/accounting/subscriptions/status` | Get user subscription status | [View](../operations/get-accounting-subscriptions-status.md) |
| GET | `/accounting/subscriptions/status/batch` | Get a bunch of subscriptions status | [View](../operations/get-accounting-subscriptions-status-batch.md) |
| GET | `/accounting/vouchers` | List vouchers | [View](../operations/get-accounting-vouchers.md) |
| POST | `/accounting/vouchers` | Create a new voucher | [View](../operations/post-accounting-vouchers.md) |
| GET | `/accounting/vouchers/namespace/{uuid}/bill` | Get voucher bill grouped data | [View](../operations/get-accounting-vouchers-namespace-uuid-bill.md) |
| GET | `/accounting/vouchers/namespace/{uuid}/dashboard` | Get voucher dashboard data | [View](../operations/get-accounting-vouchers-namespace-uuid-dashboard.md) |
| GET | `/accounting/vouchers/namespace/{uuid}/list` | List vouchers for a namespace | [View](../operations/get-accounting-vouchers-namespace-uuid-list.md) |
| GET | `/accounting/vouchers/{id}` | Get a voucher by ID | [View](../operations/get-accounting-vouchers-id.md) |
| PUT | `/accounting/vouchers/{id}` | Update a voucher | [View](../operations/put-accounting-vouchers-id.md) |
| DELETE | `/accounting/vouchers/{id}` | Delete a voucher | [View](../operations/delete-accounting-vouchers-id.md) |
| PUT | `/accounting/vouchers/{id}/revoke` | Revoke a voucher | [View](../operations/put-accounting-vouchers-id-revoke.md) |
| POST | `/accounting/weekly_recharges` | Send weekly recharges report | [View](../operations/post-accounting-weekly-recharges.md) |
