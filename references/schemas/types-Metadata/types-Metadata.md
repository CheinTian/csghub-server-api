# types.Metadata

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `architecture` | string | No |  |
| `class_name` | string | No |  |
| `has_mtp_weights` | boolean | No | Multi-token prediction capability detected by the model scan (see
HasMTPWeights). Carried through the model API so multi-sync keeps the
local metadata columns in sync instead of resetting them to zero. |
| `mini_gpu_finetune_gb` | number | No |  |
| `mini_gpu_memory_gb` | number | No |  |
| `model_params` | number | No |  |
| `model_params_valid` | boolean | No |  |
| `model_type` | string | No |  |
| `num_nextn_predict_layers` | integer | No |  |
| `pd_recommendation` | [types.PDRecommendation](types-PDRecommendation.md) | No |  |
| `quantizations` | types.Quantization[] | No |  |
| `tensor_type` | string | No |  |

