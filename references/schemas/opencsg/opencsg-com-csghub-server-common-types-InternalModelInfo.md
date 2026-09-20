# opencsg_com_csghub-server_common_types.InternalModelInfo

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cluster_id` | string | No | deploy.ClusterID |
| `created_at` | integer | No | deploy.CreatedAt.Unix() |
| `csghub_model_id` | string | No | deploy.Repository.Path |
| `engine_args` | string | No | deploy.EngineArgs |
| `hf_path` | string | No | deploy.Repository.HFPath |
| `host` | string | No | k8s Host header override (hostname from deploy endpoint) |
| `image_id` | string | No | deploy.ImageID |
| `legacy_model_id` | string | No | BuildModelID result (matches public model ID) |
| `owner_namespace` | string | No | billing/listing namespace (username or org) |
| `owner_type` | string | No | "user" or "organization" |
| `owner_username` | string | No | deploy.User.Username |
| `owner_uuid` | string | No | deploy.User.UUID |
| `repo_name` | string | No | deploy.Repository.Name |
| `runtime_framework` | string | No | deploy.RuntimeFramework |
| `secure_level` | integer | No | 1-public, 2-private, 3-extension in future |
| `source_deploy_id` | integer | No | deploy.ID |
| `svc_name` | string | No | deploy.SvcName |
| `svc_type` | integer | No | deploy.Type |
| `task` | string | No | deploy.Task |

