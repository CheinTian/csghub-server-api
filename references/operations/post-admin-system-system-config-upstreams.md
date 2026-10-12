# POST /admin/system/system_config/upstreams

**Resource:** [Admin System Config](../resources/Admin-System-Config.md)
**Create an upstream for system configuration**
**Operation ID:** `post--admin-system-system_config-upstreams`

Requires system/system_config administrator permission.

## Request Body

Upstream configuration

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateUpstreamReq](../schemas/types-CreateUpstreamReq/types-CreateUpstreamReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

## Security

- **ApiKey**
