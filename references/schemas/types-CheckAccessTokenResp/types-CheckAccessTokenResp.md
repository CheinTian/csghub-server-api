# types.CheckAccessTokenResp

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `application` | [types.AccessTokenApp](types-AccessTokenApp.md) | No |  |
| `created_at` | string | No |  |
| `expire_at` | string | No |  |
| `id` | integer | No |  |
| `ns_uuid` | string | No |  |
| `permission` | string | No |  |
| `quotas` | types.AccountAccessTokenQuotaResp[] | No |  |
| `token` | string | No |  |
| `token_name` | string | No |  |
| `token_type` | string | No |  |
| `updated_at` | string | No |  |
| `user_name` | string | No | the login name |
| `user_uuid` | string | No |  |

