# GET /external_llms

**Resource:** [LLMService](../resources/LLMService.md)
**List External LLMs**
**Operation ID:** `get--external_llms`

Get all external LLM configs (type=16) with associated repository information. This is a public endpoint that returns LLM configurations for AI Gateway, including optional repo details if repo_id is set.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 500 | Internal server error |

