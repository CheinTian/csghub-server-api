# DELETE /user/{username}

**Resource:** [User](../resources/User.md)
**Delete user**
**Operation ID:** `delete--user-{username}`

Active administrator roles must be revoked before deletion. This endpoint schedules an asynchronous workflow; administrator membership is checked again in the deletion transaction before related data is removed.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | path | string | Yes | username |
| `current_user` | query | string | Yes | current user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 409 | The user is the last administrator of an organization |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
