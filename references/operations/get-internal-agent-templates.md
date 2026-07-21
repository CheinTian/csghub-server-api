# GET /internal/agent/templates

**Resource:** [Agent](../resources/Agent.md)
**List internal agent templates**
**Operation ID:** `get--internal-agent-templates`

Get agent templates owned by the system user

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | search text |
| `type` | query | enum: langflow, code | No | type |
| `per` | query | integer | No | per |
| `page` | query | integer | No | per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 500 | Internal server error |

## Security

- **ApiKey**
