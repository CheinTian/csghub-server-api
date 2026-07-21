# GET /codes/{namespace}/{name}/download_archive/refs/{ref}/

**Resource:** [Code](../resources/Code.md)
**Download code repository as zip archive**
**Operation ID:** `get--codes-{namespace}-{name}-download_archive-refs-{ref}-`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | repo owner name |
| `name` | path | string | Yes | repo name |
| `ref` | path | string | Yes | branch or tag name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

