# GET /config/llms/logs

**Resource:** [LLMService](../resources/LLMService.md)
**List AI Gateway model request logs**
**Operation ID:** `get--config-llms-logs`

List raw AI Gateway metric events (one per inference request) within a mandatory time range (max 31 days), with optional filters by model, status code, username, masked API key, request ID and llm config. Ordered by request start time, newest first.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | define which batch of results to retrieve |
| `per` | query | integer | No | define the batch size to return in a single response |
| `start_time` | query | string | Yes | start time, format: '2026-09-16 15:52:00' |
| `end_time` | query | string | Yes | end time, format: '2026-09-16 15:52:00'; range must not exceed 31 days |
| `model` | query | string | No | exact model name match |
| `status_code` | query | integer | No | exact status code match |
| `username` | query | string | No | exact username match |
| `api_key` | query | string | No | exact masked API key match |
| `request_id` | query | string | No | exact request ID match |
| `llm_config_id` | query | integer | No | restrict to upstreams of this llm config |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

