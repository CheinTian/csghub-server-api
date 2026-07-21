# GET /api/v1/federation-adapter/redirect

**Resource:** [Federation](../resources/Federation.md)
**Verify federation token and redirect**
**Operation ID:** `get--api-v1-federation-adapter-redirect`

Verify an external federation-site-issued token from query string and redirect to the specified page on this site

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | External federation token |
| `redirect_uri` | query | string | Yes | Target redirect URI on this site |

## Responses

| Status | Description |
|--------|-------------|
| 302 | Found |
| 400 | Bad request |
| 401 | Unauthorized |
| 500 | Internal server error |

