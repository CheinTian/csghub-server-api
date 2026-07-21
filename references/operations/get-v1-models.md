# GET /v1/models

**Resource:** [AIGateway](../resources/AIGateway.md)
**List available models**
**Operation ID:** `get--v1-models`

Returns a list of available models, supports fuzzy search by model_id query parameter and filtering by llm_types, task, and associated CSGHub model repository

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `model_id` | query | string | No | Model ID for fuzzy search |
| `llm_types` | query | string[] | No | Filter by LLM types |
| `task` | query | string | No | Filter by task (e.g., text-generation, text-to-image, image-to-image) |
| `has_associated_model` | query | boolean | No | Filter by whether models are linked to a CSGHub model repository |
| `per` | query | integer | No | Models per page, must be provided with page (max 100) |
| `page` | query | integer | No | Page number, must be provided with per (1-based) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Invalid llm_types, has_associated_model, or pagination parameter |
| 500 | Internal server error |

**Success Response Schema:**

[types.ModelList](../schemas/types-ModelList/types-ModelList.md)

