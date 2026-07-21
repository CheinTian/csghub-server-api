# POST /datasets/{namespace}/{name}/refork

**Resource:** [Dataset](../resources/Dataset.md)
**Refork a dataset**
**Operation ID:** `post--datasets-{namespace}-{name}-refork`

Refork a dataset after user deletion, requires purchase check

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | namespace |
| `name` | path | string | Yes | name |
| `current_user` | query | string | No | current user |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.CreateForkReq](../schemas/types-CreateForkReq/types-CreateForkReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
