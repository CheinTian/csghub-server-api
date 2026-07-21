# types.OAuthExchangeTokenReq

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `access_token` | string | Yes | AccessToken is the Casdoor-issued JWT access token. |
| `scopes` | string[] | No | Scopes is a reserved field for future authorization checks.
The current implementation keeps the parameter for forward compatibility
but does not validate or enforce any scope values yet. |

