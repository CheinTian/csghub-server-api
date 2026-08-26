# POST /accounting/credit/{uuid}/deduct

**Resource:** [Accounting](../resources/Accounting.md)
**Sync deduct credit**
**Operation ID:** `post--accounting-credit-{uuid}-deduct`

Synchronously deduct credit from a user account for a specific scene and resource.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `uuid` | path | string | Yes | User UUID |

## Request Body

Sync deduct request body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.SyncDeductReq](../schemas/types-SyncDeductReq/types-SyncDeductReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deducted credit |
| 400 | Bad request, invalid parameters |
| 500 | Internal server error |

**Success Response Schema:**

[types.SyncDeductResp](../schemas/types-SyncDeductResp/types-SyncDeductResp.md)

## Security

- **ApiKey**
