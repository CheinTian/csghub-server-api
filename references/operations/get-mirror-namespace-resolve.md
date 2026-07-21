# GET /mirror/namespace/resolve

**Resource:** [Mirror](../resources/Mirror.md)
**Resolve target namespace and name from source**
**Operation ID:** `get--mirror-namespace-resolve`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `source_namespace` | query | string | Yes | source namespace |
| `source_name` | query | string | Yes | source name |
| `repo_type` | query | string | Yes | repo type (model, dataset, code) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
