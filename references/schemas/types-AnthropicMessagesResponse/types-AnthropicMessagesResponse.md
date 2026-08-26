# types.AnthropicMessagesResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `content` | types.AnthropicContentBlock[] | No |  |
| `id` | string | No | "msg_xxx" |
| `model` | string | No |  |
| `role` | string | No | "assistant" |
| `stop_reason` | string | No |  |
| `stop_sequence` | string | No |  |
| `type` | string | No | "message" |
| `usage` | [types.AnthropicMessagesUsage](types-AnthropicMessagesUsage.md) | No |  |

