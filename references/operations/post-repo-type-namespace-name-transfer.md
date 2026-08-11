# POST /{repo_type}/{namespace}/{name}/transfer

**Resource:** [Repository](../resources/Repository.md)
**Transfer repository ownership to another namespace**
**Operation ID:** `post--{repo_type}-{namespace}-{name}-transfer`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace` | path | string | Yes | current namespace |
| `name` | path | string | Yes | repository name |

## Request Body

transfer request

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.TransferRepoReq](../schemas/types-TransferRepoReq/types-TransferRepoReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 403 | Forbidden |
| 500 | Internal server error |

**Success Response Schema:**

[types.Response](../schemas/types-Response/types-Response.md)

## Security

- **ApiKey**
