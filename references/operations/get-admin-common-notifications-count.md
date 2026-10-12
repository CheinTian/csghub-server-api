# GET /admin/common/notifications/count

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Count the current administrator user's unread notifications**
**Operation ID:** `get--admin-common-notifications-count`

Requires an active administrator role; original business authorization and data scope are preserved.

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
