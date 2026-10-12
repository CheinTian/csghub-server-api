# types.UpstreamQueueStatus

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `current_concurrency` | integer | No | CurrentConcurrency is the number of in-flight leases (executing
requests) on the upstream at read time. |
| `high_priority_waiting` | integer | No | HighPriorityWaiting is the number of waiting tickets whose queue
priority is high (promoted first). |
| `low_priority_waiting` | integer | No | LowPriorityWaiting is the number of waiting tickets whose queue
priority is low. |
| `queue_depth` | integer | No | QueueDepth is the total number of tickets waiting in the upstream's
admission reservation queue (high + low priority). |
| `upstream_id` | integer | No |  |

