# PUT /admin/scenario_constraints/{id}

**Resource:** [SpaceReource](../resources/SpaceReource.md)
**Update scenario constraint**
**Operation ID:** `put--admin-scenario_constraints-{id}`

update scenario constraint

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | scenario constraint id |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.UpdateScenarioConstraintReq](../schemas/types-UpdateScenarioConstraintReq/types-UpdateScenarioConstraintReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 404 | Not found |
| 500 | Internal server error |

## Security

- **ApiKey**
