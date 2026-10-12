# GET /accounting/token-plans/{uuid}/get

**Resource:** [Accounting](../resources/Accounting.md)
**Get current token plan for a namespace**
**Operation ID:** `get--accounting-token-plans-{uuid}-get`

Get the current active token plan subscription for the namespace

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | namespace uuid |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 404 | Not found |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
