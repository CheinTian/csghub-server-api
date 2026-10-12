# GET /internal/licenses/status

**Resource:** [License](../resources/License.md)
**Get active license status for internal services**
**Operation ID:** `get--internal-licenses-status`

Requires the system API key. Returns active license status without a user identity or administrator grant.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 500 | Internal Server Error |

## Security

- **ApiKey**
