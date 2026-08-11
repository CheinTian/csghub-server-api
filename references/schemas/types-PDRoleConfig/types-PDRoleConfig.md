# types.PDRoleConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dp` | integer | No | DP is the data parallelism degree (always 1 in PD planning).
TotalGPUs = TP (DP=1, EP follows TP and does not add extra GPUs). |
| `ep` | integer | No | EP is the expert parallelism degree (1 for dense models). |
| `pods` | integer | No | Pods is the number of pods per LWS group (maps to LWS spec.leaderWorkerTemplate.size).
Each pod runs one vLLM/SGLang instance.
Example: TotalGPUs=8, GPUsPerPod=4 → Pods=2 → LWS Size=2 → 2 pods × 4 GPUs each.
When Pods=1 and TotalGPUs=4, all 4 GPUs are in a single pod;
HardWare.Replicas is set to Pods (1), and Gpu.Num is set to TotalGPUs/Pods (4).
The LWS Replicas field (number of LWS groups) is controlled separately by
PDConfig.PrefillReplicas/DecodeReplicas (default 1), which HPA scales up/down. |
| `total_gpus` | integer | No | TotalGPUs is the total number of GPUs required (TP, since DP=1 and EP follows TP). |
| `total_vram_gb` | number | No | TotalVRAMGB is the total VRAM required for this role, computed as
MinInferenceVRAMGB * Pods. Used for VRAM validation and hardware splitting ratio. |
| `tp` | integer | No | TP is the tensor parallelism degree. |

