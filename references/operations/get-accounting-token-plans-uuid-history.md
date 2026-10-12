# GET /accounting/token-plans/{uuid}/history

**Resource:** [Accounting](../resources/Accounting.md)
**List token plan history for a namespace**
**Operation ID:** `get--accounting-token-plans-{uuid}-history`

List token plan subscription history for the namespace

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | namespace uuid |
| `per` | query | integer | No | per page |
| `page` | query | integer | No | page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
