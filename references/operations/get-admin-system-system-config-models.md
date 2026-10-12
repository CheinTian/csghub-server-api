# GET /admin/system/system_config/models

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**List models for system configuration**
**Operation ID:** `get--admin-system-system_config-models`

Requires system/system_config administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | Model search text |
| `page` | query | integer | No | Page number |
| `per` | query | integer | No | Page size |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
