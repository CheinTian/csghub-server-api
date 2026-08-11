# GET /models/{namespace}/{name}/serverless/{id}/logs

**Resource:** [Model](../resources/Model.md)
**get serverless stream logs**
**Operation ID:** `get--models-{namespace}-{name}-serverless-{id}-logs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repo_type` | path | enum: models | Yes | models |
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `id` | path | string | Yes | id |
| `current_user` | query | string | Yes | current_user |
| `limit` | query | integer | No | max number of log lines to return |
| `since` | query | string | No | since time. Optional values: 10mins, 30mins, 1hour, 6hours, 1day, 2days, 1week |

## Responses

| Status | Description |
|--------|-------------|
| 400 | Bad request. May occur when the since time format is unsupported |
| 500 | Internal server error |

## Security

- **ApiKey**
