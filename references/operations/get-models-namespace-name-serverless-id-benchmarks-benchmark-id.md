# GET /models/{namespace}/{name}/serverless/{id}/benchmarks/{benchmark_id}

**Resource:** [Model](../resources/Model.md)
**Get serverless benchmark detail**
**Operation ID:** `get--models-{namespace}-{name}-serverless-{id}-benchmarks-{benchmark_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `id` | path | string | Yes | deploy id |
| `benchmark_id` | path | string | Yes | benchmark id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
