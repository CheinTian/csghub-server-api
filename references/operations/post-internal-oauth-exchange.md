# POST /internal/oauth/exchange

**Resource:** [Token](../resources/Token.md)
**Exchange an OAuth access token for a local JWT**
**Operation ID:** `post--internal-oauth-exchange`

Validate a Casdoor-issued JWT access token and return a locally issued JWT with mapped user identity

## Request Body

OAuth token exchange request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.OAuthExchangeTokenReq](../schemas/types-OAuthExchangeTokenReq/types-OAuthExchangeTokenReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 500 | Internal server error |

## Security

- **ApiKey**
