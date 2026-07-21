# AgentCredential

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/agent/credentials` | List agent credentials | [View](../operations/get-agent-credentials.md) |
| POST | `/agent/credentials` | Create an agent credential | [View](../operations/post-agent-credentials.md) |
| GET | `/agent/credentials/providers` | List supported agent credential providers | [View](../operations/get-agent-credentials-providers.md) |
| POST | `/agent/credentials/runtime/session/revoke` | Revoke a runtime credential session | [View](../operations/post-agent-credentials-runtime-session-revoke.md) |
| GET | `/agent/credentials/runtime/{credential_name}` | Get runtime credential material | [View](../operations/get-agent-credentials-runtime-credential-name.md) |
| GET | `/agent/credentials/sessions/{session_id}/grants` | List agent credential grants | [View](../operations/get-agent-credentials-sessions-session-id-grants.md) |
| POST | `/agent/credentials/sessions/{session_id}/grants` | Create agent credential grants | [View](../operations/post-agent-credentials-sessions-session-id-grants.md) |
| POST | `/agent/credentials/verify` | Verify an agent credential connection | [View](../operations/post-agent-credentials-verify.md) |
| GET | `/agent/credentials/{credential_name}` | Get an agent credential | [View](../operations/get-agent-credentials-credential-name.md) |
| DELETE | `/agent/credentials/{credential_name}` | Delete an agent credential | [View](../operations/delete-agent-credentials-credential-name.md) |
| PATCH | `/agent/credentials/{credential_name}` | Update an agent credential | [View](../operations/patch-agent-credentials-credential-name.md) |
| POST | `/agent/credentials/{credential_name}/revoke` | Revoke an agent credential | [View](../operations/post-agent-credentials-credential-name-revoke.md) |
| POST | `/agent/credentials/{credential_name}/rotate` | Rotate an agent credential secret | [View](../operations/post-agent-credentials-credential-name-rotate.md) |
