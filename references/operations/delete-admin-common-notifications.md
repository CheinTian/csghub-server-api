# DELETE /admin/common/notifications

**Resource:** [Admin Common](../resources/Admin-Common.md)
**Delete the current administrator user's notifications**
**Operation ID:** `delete--admin-common-notifications`

Requires an active administrator role; original business authorization and data scope are preserved.

## Request Body

Notifications to delete

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
