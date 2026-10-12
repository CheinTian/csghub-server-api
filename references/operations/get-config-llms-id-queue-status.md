# GET /config/llms/{id}/queue_status

**Resource:** [LLMService](../resources/LLMService.md)
**Get upstream queue status of an LLM config**
**Operation ID:** `get--config-llms-{id}-queue_status`

Return the live admission-queue snapshot for every queue-enabled upstream of the LLM config: total waiting tickets, waiting tickets by priority (high/low) and the in-flight concurrency, read from the AI Gateway's Redis queue state. Upstreams without an enabled queue policy are omitted; the snapshot is read at request time and changes with traffic.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | LLMConfig.ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

