# types.PDRoleRuntimeConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dp` | integer | No | DP is the data parallelism degree. |
| `ep` | integer | No | EP is the expert parallelism degree (1 for dense models). |
| `hardware` | object | No | Hardware is the hardware resource allocated to this role. |
| `pods_size` | integer | No | PodsSize is the LWS Group Size — the number of pods per LWS group
(maps to LWS spec.leaderWorkerTemplate.size).
Each pod runs one vLLM/SGLang instance. GPUs per pod = TotalGPUs / PodsSize.
To scale the number of LWS groups (replicas), use PrefillReplicas/DecodeReplicas
(controlled by HPA via MinReplica/MaxReplica), NOT PodsSize.
When PodsSize is 0 or 1, all GPUs are in a single pod. |
| `total_gpus` | integer | No | TotalGPUs is the total GPUs for this role (TP * DP). EP does not add extra GPUs. |
| `tp` | integer | No | TP is the tensor parallelism degree (global, across all pods in the LWS group). |

