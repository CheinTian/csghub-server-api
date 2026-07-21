# POST /admin/datasets/applications/review

**Resource:** [Dataset](../resources/Dataset.md)
**Review a dataset application (admin)**
**Operation ID:** `post--admin-datasets-applications-review`

approve or reject a dataset application

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `current_user` | query | string | No | current user |

## Request Body

body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [types.ReviewDatasetApplicationReq](../schemas/types-ReviewDatasetApplicationReq/types-ReviewDatasetApplicationReq.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
