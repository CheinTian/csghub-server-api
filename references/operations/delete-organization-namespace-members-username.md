# DELETE /organization/{namespace}/members/{username}

**Resource:** [Member](../resources/Member.md)
**Remove membership between org and user**
**Operation ID:** `delete--organization-{namespace}-members-{username}`

Remove a user's membership from an organization. The member role is resolved from the database.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | org name |
| `username` | path | string | Yes | user name |
| `current_user` | query | string | No | the op user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
