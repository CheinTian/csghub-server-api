# POST /models/{namespace}/{name}/serverless/{id}/benchmark

**Resource:** [Model](../resources/Model.md)
**Trigger serverless benchmark**
**Operation ID:** `post--models-{namespace}-{name}-serverless-{id}-benchmark`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `id` | path | string | Yes | deploy id |

## Request Body

benchmark trigger config

**Content Types:** `application/json`

**Schema:** [types.DeployBenchmarkTriggerReq](../schemas/types-DeployBenchmarkTriggerReq/types-DeployBenchmarkTriggerReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
