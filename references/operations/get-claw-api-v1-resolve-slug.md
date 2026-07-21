# GET /claw/api/v1/resolve/{slug}

**Resource:** [ClawHub](../resources/ClawHub.md)
**Resolve skill by path for ClawHub install**
**Operation ID:** `get--claw-api-v1-resolve-{slug}`

Resolve skill version for ClawHub install

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slug` | path | string | Yes | skill slug |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[types.ClawHubResolveResponse](../schemas/types-ClawHubResolveResponse/types-ClawHubResolveResponse.md)

