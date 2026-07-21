# POST /datasets/{namespace}/{name}/buy

**Resource:** [Dataset](../resources/Dataset.md)
**Buy a dataset**
**Operation ID:** `post--datasets-{namespace}-{name}-buy`

buy a commercial dataset

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

**Schema:** [types.BuyDatasetReq](../schemas/types-BuyDatasetReq/types-BuyDatasetReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
