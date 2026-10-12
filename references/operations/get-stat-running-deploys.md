# GET /stat/running-deploys

**Resource:** [Stat](../resources/Stat.md)
**Get running deploy statistics**
**Operation ID:** `get--stat-running-deploys`

Retrieve the number of running deployments, CPU usage, and GPU usage per project. Requires system/dashboard admin permission.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 500 | Internal server error |

## Security

- **ApiKey**
