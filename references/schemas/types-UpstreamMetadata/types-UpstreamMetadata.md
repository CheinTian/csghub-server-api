# types.UpstreamMetadata

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `host_override` | string | No |  |
| `internal_model_info` | [opencsg_com_csghub-server_common_types.InternalModelInfo](opencsg-com-csghub-server-common-types-InternalModelInfo.md) | No |  |
| `protocol` | string | No | Protocol is an explicit upstream protocol declaration (chat/responses/messages).
When set, it overrides URL-based protocol inference. |
| `responses_chat_adapter` | [types.ResponsesChatAdapter](types-ResponsesChatAdapter.md) | No |  |

