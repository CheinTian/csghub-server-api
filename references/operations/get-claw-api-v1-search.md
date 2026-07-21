# GET /claw/api/v1/search

**Resource:** [ClawHub](../resources/ClawHub.md)
**Search skills for ClawHub**
**Operation ID:** `get--claw-api-v1-search`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `q` | query | string | Yes | search query |
| `limit` | query | integer | No | limit |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[types.ClawHubSearchResponse](../schemas/types-ClawHubSearchResponse/types-ClawHubSearchResponse.md)

