# GET /user/{username}/organizations

**Resource:** [Organization](../resources/Organization.md)
**Get organizations the user belongs to**
**Operation ID:** `get--user-{username}-organizations`
⚠️ **Deprecated**

get organizations the specified user belongs to, with optional role filter (all, write, admin)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | path | string | Yes | username |
| `search` | query | string | No | search keyword |
| `org_type` | query | string | No | org type filter |
| `verify_status` | query | string | No | verify status filter |
| `role` | query | string | No | role filter: all (any member), write, admin |
| `tag` | query | string | No | filter by tag name |
| `per` | query | integer | No | page size |
| `page` | query | integer | No | page number |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 500 | Internal server error |

## Security

- **ApiKey**
