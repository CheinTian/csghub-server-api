# PUT /admin/common/notifications/setting

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Update the current administrator user's notification settings**
**Operation ID:** `put--admin-common-notifications-setting`

Requires an active administrator role; original business authorization and data scope are preserved.

## Request Body

Notification settings

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateNotificationReq](../schemas/types-UpdateNotificationReq/types-UpdateNotificationReq.md)

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
