# Admin Common

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/common/broadcasts/active` | Get the active broadcast for the administrator navigation bar | [View](../operations/get-admin-common-broadcasts-active.md) |
| POST | `/admin/common/jwt/token` | Refresh the current administrator JWT | [View](../operations/post-admin-common-jwt-token.md) |
| GET | `/admin/common/notifications` | List the current administrator user's notifications | [View](../operations/get-admin-common-notifications.md) |
| DELETE | `/admin/common/notifications` | Delete the current administrator user's notifications | [View](../operations/delete-admin-common-notifications.md) |
| GET | `/admin/common/notifications/count` | Count the current administrator user's unread notifications | [View](../operations/get-admin-common-notifications-count.md) |
| GET | `/admin/common/notifications/message-types` | List notification types for the administrator navigation bar | [View](../operations/get-admin-common-notifications-message-types.md) |
| GET | `/admin/common/notifications/poll/{limit}` | Poll the current administrator user's new notifications | [View](../operations/get-admin-common-notifications-poll-limit.md) |
| PUT | `/admin/common/notifications/read` | Mark the current administrator user's notifications as read | [View](../operations/put-admin-common-notifications-read.md) |
| GET | `/admin/common/notifications/setting` | Get the current administrator user's notification settings | [View](../operations/get-admin-common-notifications-setting.md) |
| PUT | `/admin/common/notifications/setting` | Update the current administrator user's notification settings | [View](../operations/put-admin-common-notifications-setting.md) |
| GET | `/admin/common/organizations/mine` | List my organizations for administrator navigation | [View](../operations/get-admin-common-organizations-mine.md) |
| GET | `/admin/common/tags` | Get tag choices for the administrator navigation bar | [View](../operations/get-admin-common-tags.md) |
| POST | `/admin/common/user/email-verification-code/{email}` | Send a profile email verification code | [View](../operations/post-admin-common-user-email-verification-code-email.md) |
| POST | `/admin/common/user/tags` | Set the current administrator user's industry tags | [View](../operations/post-admin-common-user-tags.md) |
| GET | `/admin/common/user/{identifier}` | Get a profile for the administrator navigation bar | [View](../operations/get-admin-common-user-identifier.md) |
| PUT | `/admin/common/user/{identifier}` | Update a profile from the administrator navigation bar | [View](../operations/put-admin-common-user-identifier.md) |
| GET | `/admin/common/version` | Get the server version for the administrator navigation bar | [View](../operations/get-admin-common-version.md) |
