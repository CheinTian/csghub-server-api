# GET /admin/common/notifications/poll/{limit}

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Poll the current administrator user's new notifications**
**Operation ID:** `get--admin-common-notifications-poll-{limit}`

Requires an active administrator role; original business authorization and data scope are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | path | integer | Yes | Maximum number of notifications |
| `timezone` | query | string | No | Timezone |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

## Security

- **ApiKey**
