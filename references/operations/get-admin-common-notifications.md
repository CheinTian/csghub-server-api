# GET /admin/common/notifications

**Resource:** [Admin Common](../resources/Admin-Common.md)
**List the current administrator user's notifications**
**Operation ID:** `get--admin-common-notifications`

Requires an active administrator role; original business authorization and data scope are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Page number |
| `page_size` | query | integer | No | Page size |
| `notification_type` | query | string | No | Notification type |
| `unread_only` | query | boolean | No | Only unread notifications |
| `title` | query | string | No | Notification title |

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
