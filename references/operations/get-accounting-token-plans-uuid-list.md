# GET /accounting/token-plans/{uuid}/list

**Resource:** [Accounting](../resources/Accounting.md)
**List token plans for a namespace**
**Operation ID:** `get--accounting-token-plans-{uuid}-list`

List published token plans available to the namespace

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | namespace uuid |

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
