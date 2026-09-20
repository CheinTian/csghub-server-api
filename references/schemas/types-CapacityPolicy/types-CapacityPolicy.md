# types.CapacityPolicy

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Enabled turns on capacity tracking and enforcement for this upstream. |
| `max_concurrency` | integer | No | MaxConcurrency is the maximum number of in-flight requests. |
| `max_queue_depth` | integer | No | MaxQueueDepth is the maximum number of requests waiting for a slot. |
| `max_rpm` | integer | No | MaxRPM is the maximum number of requests per minute. 0 = unlimited.
Ignored (and required to be 0) in queue mode. |
| `max_tpm` | integer | No | MaxTPM is the maximum number of tokens per minute. 0 = unlimited.
Ignored (and required to be 0) in queue mode. |
| `queue_wait_seconds` | integer | No | QueueWaitSeconds is how long a request may wait in the upstream queue
before being rejected. |

