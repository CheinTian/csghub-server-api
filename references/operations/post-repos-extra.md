# POST /repos/extra

**Resource:** [Repository](../resources/Repository.md)
**Batch get extra information for multiple repositories**
**Operation ID:** `post--repos-extra`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `current_user` | query | string | No | current user name |

## Request Body

request body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.BatchRepoExtraReq](../schemas/types-BatchRepoExtraReq/types-BatchRepoExtraReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
