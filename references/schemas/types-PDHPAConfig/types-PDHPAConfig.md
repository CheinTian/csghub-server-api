# types.PDHPAConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Enabled controls whether HPA is created for prefill and decode LWS.
Default: true (when PDConfig.HPA is nil, HPA is enabled by default) |
| `max_replicas` | integer | No | MaxReplicas is the maximum number of LWS replicas (leader pods) for both prefill and decode.
The HPA will never scale above this value.
Default: maxReplica from request, or 2 if not specified |
| `min_replicas` | integer | No | MinReplicas is the minimum number of LWS replicas (leader pods) for both prefill and decode.
The HPA will never scale below this value.
Default: 1 |
| `queue_threshold` | integer | No | QueueThreshold is the EPP pending queue size threshold for scale-up decisions.
When the average queue size across all decode pods exceeds this value,
the HPA will scale up decode replicas.
Default: 3 |
| `running_threshold` | integer | No | RunningThreshold is the EPP running requests threshold for scale-up decisions.
When the average number of running requests per decode pod exceeds this value,
the HPA will scale up decode replicas.
Default: 100 |
| `scale_down_cooldown` | integer | No | ScaleDownCooldown is the stabilization window in seconds for scale-down decisions.
The HPA will not scale down within this window after a scale-up event,
preventing flapping during transient load changes.
Default: 300 (5 minutes) |
| `scale_up_cooldown` | integer | No | ScaleUpCooldown is the stabilization window in seconds for scale-up decisions.
The HPA will only scale up after the metric exceeds the threshold for this duration,
preventing scaling on transient spikes.
Default: 60 (1 minute) |

