# GET /evaluations/{id}/logs

**Resource:** [Evaluation](../resources/Evaluation.md)
**get evaluation job logs**
**Operation ID:** `get--evaluations-{id}-logs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | evaluation job id or task id |
| `since` | query | string | No | since time. Optional values: 10mins, 30mins, 1hour, 6hours, 1day, 2days, 1week |

## Responses

| Status | Description |
|--------|-------------|
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
