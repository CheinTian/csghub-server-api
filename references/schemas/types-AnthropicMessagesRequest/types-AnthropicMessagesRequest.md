# types.AnthropicMessagesRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `max_tokens` | integer | No |  |
| `messages` | types.AnthropicMessage[] | No |  |
| `metadata` | [types.AnthropicMetadata](types-AnthropicMetadata.md) | No |  |
| `model` | string | No |  |
| `stop_sequences` | string[] | No |  |
| `stream` | boolean | No |  |
| `system` | integer[] | No | string or []AnthropicContentBlock |
| `temperature` | number | No |  |
| `thinking` | [types.AnthropicThinking](types-AnthropicThinking.md) | No |  |
| `tool_choice` | integer[] | No |  |
| `tools` | types.AnthropicTool[] | No |  |
| `top_k` | integer | No |  |
| `top_p` | number | No |  |

