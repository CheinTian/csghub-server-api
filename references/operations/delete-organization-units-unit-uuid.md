# DELETE /organization-units/{unit_uuid}

**Resource:** [OrganizationUnit](../resources/OrganizationUnit.md)
**Delete an organization department subtree**
**Operation ID:** `delete--organization-units-{unit_uuid}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `unit_uuid` | path | string | Yes | Department UUID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not Found |

## Security

- **ApiKey**
