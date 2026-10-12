# DELETE /admin/account/organization/organization-units/{unit_uuid}

**Resource:** [Admin Account Organization](../resources/Admin-Account-Organization.md)
**Delete an organization department subtree for administration**
**Operation ID:** `delete--admin-account-organization-organization-units-{unit_uuid}`

Requires account/organization permission at both services. Original payloads, business validation and downstream responses are preserved.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `unit_uuid` | path | string | Yes | Department UUID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

## Security

- **ApiKey**
