# types.JevRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `model` | string | No |  |
| `questions` | object | No | Questions holds the named typed questions submitted to the model. |
| `state` | integer[] | No | State is the situation to evaluate. The protocol allows any JSON
value: a plain string or a structured object/array (e.g. a state
carrying ticket, order, and policy fields). It is kept as raw JSON so
structured states survive the gateway round-trip unchanged. |

