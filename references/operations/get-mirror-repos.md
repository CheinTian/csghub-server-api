# GET /mirror/repos

**Resource:** [Mirror](../resources/Mirror.md)
**Get repositories in the multi-source synchronization queue**
**Operation ID:** `get--mirror-repos`

Requires asset/sync administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `per` | query | integer | No | per |
| `page` | query | integer | No | page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal server error |

## Security

- **ApiKey**
