# POST /datasets/{namespace}/{name}/application

**Resource:** [Dataset](../resources/Dataset.md)
**Create a dataset application (publish/unpublish)**
**Operation ID:** `post--datasets-{namespace}-{name}-application`

create a dataset application for publish or unpublish

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `current_user` | query | string | No | current user |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateDatasetApplicationReq](../schemas/types-CreateDatasetApplicationReq/types-CreateDatasetApplicationReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
