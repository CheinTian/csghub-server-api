# GET /models/{namespace}/{name}/serverless/{id}/logs/last

**Resource:** [Model](../resources/Model.md)
**get serverless last logs in number of lines**
**Operation ID:** `get--models-{namespace}-{name}-serverless-{id}-logs-last`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `id` | path | string | Yes | id |
| `instance` | query | string | Yes | instance |
| `limit` | query | integer | No | max number of log lines to return |
| `since` | query | string | No | since time. Optional values: 1hour, 1day, 1week |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Permission denied |
| 500 | Internal server error |

**Success Response Schema:**

[loki.LokiQueryResponse](../schemas/loki-LokiQueryResponse/loki-LokiQueryResponse.md)

## Security

- **ApiKey**
