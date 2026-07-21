# GET /datasets/{namespace}/{name}/application

**Resource:** [Dataset](../resources/Dataset.md)
**Get current dataset application status**
**Operation ID:** `get--datasets-{namespace}-{name}-application`

get the latest application for a dataset (owner only)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `current_user` | query | string | No | current user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
