# GET /organizations

**Resource:** [Organization](../resources/Organization.md)
**Get all organizations**
**Operation ID:** `get--organizations`

get all organizations, no authentication required

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | search keyword |
| `org_type` | query | string | No | org type filter |
| `verify_status` | query | string | No | verify status filter |
| `tag` | query | string | No | filter by tag name |
| `per` | query | integer | No | page size |
| `page` | query | integer | No | page number |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 500 | Internal server error |

