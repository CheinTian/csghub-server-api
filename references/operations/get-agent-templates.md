# GET /agent/templates

**Resource:** [Agent](../resources/Agent.md)
**List public agent templates**
**Operation ID:** `get--agent-templates`

Anonymous callers receive public templates only; authenticated callers also receive their own templates

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | search text |
| `type` | query | enum: langflow, code | No | type |
| `editable` | query | boolean | No | filter by whether the template is editable by the caller (true = owned by caller) |
| `per` | query | integer | No | per |
| `page` | query | integer | No | per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 500 | Internal server error |

