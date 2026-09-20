# GET /namespaces/mine/writable

**Resource:** [Organization](../resources/Organization.md)
**Get namespaces writable by the current user**
**Operation ID:** `get--namespaces-mine-writable`

Lists namespaces where the current user has can_write permission.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 500 | Internal server error |

## Security

- **ApiKey**
