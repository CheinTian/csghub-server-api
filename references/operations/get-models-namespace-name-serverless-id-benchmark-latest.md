# GET /models/{namespace}/{name}/serverless/{id}/benchmark/latest

**Resource:** [Model](../resources/Model.md)
**Get latest serverless benchmark result**
**Operation ID:** `get--models-{namespace}-{name}-serverless-{id}-benchmark-latest`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `id` | path | string | Yes | deploy id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
