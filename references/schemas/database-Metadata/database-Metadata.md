# database.Metadata

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `architecture` | string | No |  |
| `class_name` | string | No |  |
| `created_at` | string | No |  |
| `id` | integer | No |  |
| `mini_gpu_finetune_gb` | number | No |  |
| `mini_gpu_memory_gb` | number | No |  |
| `model_arch_type` | [types.ModelArchType](types-ModelArchType.md) | No |  |
| `model_params` | number | No |  |
| `model_type` | string | No |  |
| `pd_recommendation` | [types.PDRecommendation](types-PDRecommendation.md) | No |  |
| `quantizations` | types.Quantization[] | No |  |
| `repository` | [database.Repository](database-Repository.md) | No |  |
| `repository_id` | integer | No |  |
| `tensor_type` | string | No |  |
| `updated_at` | string | No |  |

