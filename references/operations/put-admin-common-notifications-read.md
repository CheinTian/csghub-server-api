# PUT /admin/common/notifications/read

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Mark the current administrator user's notifications as read**
**Operation ID:** `put--admin-common-notifications-read`

Requires an active administrator role; original business authorization and data scope are preserved.

## Request Body

Notifications to mark as read

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.BatchNotificationOperationReq](../schemas/types-BatchNotificationOperationReq/types-BatchNotificationOperationReq.md)

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
