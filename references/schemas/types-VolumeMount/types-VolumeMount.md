# types.VolumeMount

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `mount_path` | string | No | in-container mount point |
| `pvc_name` | string | No | PVC to mount; empty uses the deploy's default/shared PVC |
| `read_only` | boolean | No |  |
| `subpath` | string | No | relative subdirectory inside the PVC |

