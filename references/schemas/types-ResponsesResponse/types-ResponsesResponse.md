# types.ResponsesResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | integer | No |  |
| `error` | object | No |  |
| `id` | string | No |  |
| `incomplete_details` | integer[] | No |  |
| `instructions` | integer[] | No |  |
| `max_output_tokens` | integer | No |  |
| `metadata` | integer[] | No |  |
| `model` | string | No |  |
| `object` | string | No |  |
| `output` | types.ResponsesOutputItem[] | No |  |
| `output_text` | string | No |  |
| `parallel_tool_calls` | boolean | No |  |
| `previous_response_id` | string | No |  |
| `reasoning` | integer[] | No |  |
| `status` | string | No |  |
| `store` | boolean | No |  |
| `temperature` | number | No |  |
| `tool_choice` | integer[] | No |  |
| `tools` | integer[] | No |  |
| `top_p` | number | No |  |
| `truncation` | integer[] | No |  |
| `usage` | [types.ResponsesUsage](types-ResponsesUsage.md) | No |  |
| `user` | string | No |  |

