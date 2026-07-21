# types.ModelRunReq

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `agent` | string | No |  |
| `cluster_id` | string | No |  |
| `deploy_name` | string | No |  |
| `enable_pd` | boolean | No | EnablePD enables PD (Prefill-Decode) disaggregation inference architecture.
When true, the system checks the model metadata for PD recommendation,
validates hardware resources, and splits resources between prefill and decode. |
| `engine_args` | string | No |  |
| `entrypoint` | string | No | model file name for gguf model |
| `env` | string | No |  |
| `max_replica` | integer | No |  |
| `min_replica` | integer | No |  |
| `order_detail_id` | integer | No |  |
| `owner_namespace` | string | No | OwnerNamespace is optional. If set, the inference is created under this namespace (user or org) for billing and listing; path {namespace} remains the model's owner. |
| `pd` | object | No | PD is the client-provided PD (Prefill-Decode) disaggregation configuration.
When EnablePD is true, the client sends TP/DP/EP/PodsSize for prefill and decode
roles. The server validates the config against available hardware resources
instead of deriving it from PDRecommendation. |
| `resource_id` | integer | No |  |
| `revision` | string | No |  |
| `runtime_framework_id` | integer | No |  |
| `secure_level` | integer | No |  |

