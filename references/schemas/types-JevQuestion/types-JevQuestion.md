# types.JevQuestion

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `criteria` | integer[] | No | Criteria is the type-specific question configuration kept as raw
JSON: a choice map for "choice" questions (required for that type),
or other JSON shapes (e.g. score definitions) for other types. |
| `instructions` | integer[] | No | Instructions tells the model how to answer the question. The
protocol's EntryType allows any JSON value (string, object, array,
or null), so it is kept as raw JSON. |
| `type` | string | No | Type is the question kind, e.g. "noul" (numeric score) or "choice". |

