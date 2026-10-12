# POST /models/{namespace}/{name}/engine_args/optimize

**Resource:** [EngineArgs](../resources/EngineArgs.md)
**Optimize engine args**
**Operation ID:** `post--models-{namespace}-{name}-engine_args-optimize`

Return optimized engine args based on runtime environment and user's current values

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |

## Request Body

request body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.OptimizeEngineArgsReq](../schemas/types-OptimizeEngineArgsReq/types-OptimizeEngineArgsReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **ApiKey**
