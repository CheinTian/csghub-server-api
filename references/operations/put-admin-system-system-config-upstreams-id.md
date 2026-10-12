# PUT /admin/system/system_config/upstreams/{id}

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**Update an upstream for system configuration**
**Operation ID:** `put--admin-system-system_config-upstreams-{id}`

Requires system/system_config administrator permission.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Upstream ID |

## Request Body

Upstream configuration

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateUpstreamReq](../schemas/types-UpdateUpstreamReq/types-UpdateUpstreamReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
