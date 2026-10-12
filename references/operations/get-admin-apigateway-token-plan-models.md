# GET /admin/apigateway/token_plan/models

**Resource:** [Admin APIGateway Token Plan](../resources/Admin-APIGateway-Token-Plan.md)
**List models for subscription plans**
**Operation ID:** `get--admin-apigateway-token_plan-models`

Requires apigateway/token_plan administrator permission. Preserves model scope, visibility, filtering, and pagination from the ordinary catalog.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `model_id` | query | string | No | Model ID for fuzzy search |
| `llm_types` | query | string[] | No | LLM types |
| `task` | query | string | No | Model task |
| `has_associated_model` | query | boolean | No | Filter by associated repository |
| `per` | query | integer | No | Models per page, maximum 100 |
| `page` | query | integer | No | Page number, starting at 1 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal Server Error |

**Success Response Schema:**

[types.ModelList](../schemas/types-ModelList/types-ModelList.md)

## Security

- **ApiKey**
