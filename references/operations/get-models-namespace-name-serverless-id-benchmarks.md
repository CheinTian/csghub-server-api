# GET /models/{namespace}/{name}/serverless/{id}/benchmarks

**Resource:** [Model](../resources/Model.md)
**List serverless benchmark results**
**Operation ID:** `get--models-{namespace}-{name}-serverless-{id}-benchmarks`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `id` | path | string | Yes | deploy id |
| `page` | query | integer | No | page number |
| `page_size` | query | integer | No | page size |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
