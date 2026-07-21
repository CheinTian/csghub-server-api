# types.PDRecommendation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_experts` | integer | No | ActiveExperts is the number of experts activated per token. |
| `decode` | object | No | Decode is the recommended decode configuration. |
| `min_inference_vram_gb` | number | No | MinInferenceVRAMGB is the minimum VRAM per GPU required to load and run inference.
TotalVRAMGB for each role is computed as MinInferenceVRAMGB * Pods. |
| `model_name` | string | No | ModelName is the model name used to resolve the spec. |
| `non_moe_params_b` | number | No | NonMoEParamsB is the non-expert parameter count in billions. |
| `precision` | string | No | Precision is the inference precision. |
| `prefill` | object | No | Prefill is the recommended prefill configuration. |
| `total_experts` | integer | No | TotalExperts is the number of routed experts (0 for dense models). |
| `total_params_b` | number | No | TotalParamsB is the total parameter count in billions. |

