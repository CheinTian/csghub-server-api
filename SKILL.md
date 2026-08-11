---
name: csghub-server-api
description: CSGHub Server API.. Use when working with the CSGHub Server API or when the user needs to interact with this API.
metadata:
  api-version: "1.0"
  openapi-version: "3.0.1"
---

# CSGHub Server API

CSGHub Server API.

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 60 resource index files
├── operations/     # 653 operation detail files
└── schemas/        # 619 schema groups, 623 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

All HTTP requests must use the base URL from the environment variable:

`CSGHUB_API_BASE_URL`

Rules:
1. Do not construct or guess the base URL manually.
2. Do not use any default or fallback URL.
3. Always prepend requests with: {CSGHUB_API_BASE_URL}
4. Treat this as the single source of truth.

## Authentication

Supported methods: **ApiKey**. See `references/authentication.md` for details.

## Resources

- **Agent** → `references/resources/Agent.md` (67 ops)
- **Repository** → `references/resources/Repository.md` (53 ops)
- **Accounting** → `references/resources/Accounting.md` (52 ops)
- **User** → `references/resources/User.md` (48 ops)
- **Model** → `references/resources/Model.md` (43 ops)
- **Prompt** → `references/resources/Prompt.md` (26 ops)
- **AIGateway** → `references/resources/AIGateway.md` (22 ops)
- **Organization** → `references/resources/Organization.md` (20 ops)
- **Cluster** → `references/resources/Cluster.md` (18 ops)
- **Mirror** → `references/resources/Mirror.md` (17 ops)
- **Accounting-Invoices** → `references/resources/Accounting-Invoices.md` (15 ops)
- **Dataset** → `references/resources/Dataset.md` (15 ops)
- **LLMService** → `references/resources/LLMService.md` (15 ops)
- **AgentCredential** → `references/resources/AgentCredential.md` (13 ops)
- **RuntimeFramework** → `references/resources/RuntimeFramework.md` (13 ops)
- **Space** → `references/resources/Space.md` (11 ops)
- **Notifications** → `references/resources/Notifications.md` (10 ops)
- **ClawHub** → `references/resources/ClawHub.md` (9 ops)
- **Discussion** → `references/resources/Discussion.md` (9 ops)
- **Notebook** → `references/resources/Notebook.md` (9 ops)
- **Skill** → `references/resources/Skill.md` (9 ops)
- **Tag** → `references/resources/Tag.md` (9 ops)
- **Access token** → `references/resources/Access-token.md` (9 ops)
- **Code** → `references/resources/Code.md` (8 ops)
- **Collection** → `references/resources/Collection.md` (8 ops)
- **License** → `references/resources/License.md` (8 ops)
- **MCP** → `references/resources/MCP.md` (7 ops)
- **MCP Servers** → `references/resources/MCP-Servers.md` (6 ops)
- **SpaceReource** → `references/resources/SpaceReource.md` (6 ops)
- **Sandbox** → `references/resources/Sandbox.md` (6 ops)
- **API Key** → `references/resources/API-Key.md` (6 ops)
- **Member** → `references/resources/Member.md` (6 ops)
- **Monitor** → `references/resources/Monitor.md` (6 ops)
- **ApiRateLimit** → `references/resources/ApiRateLimit.md` (5 ops)
- **Broadcasts** → `references/resources/Broadcasts.md` (5 ops)
- **SpaceTemplate** → `references/resources/SpaceTemplate.md` (5 ops)
- **Moderation** → `references/resources/Moderation.md` (4 ops)
- **StorageGateway** → `references/resources/StorageGateway.md` (4 ops)
- **Evaluation** → `references/resources/Evaluation.md` (4 ops)
- **Finetune** → `references/resources/Finetune.md` (4 ops)
- **SpaceSdk** → `references/resources/SpaceSdk.md` (4 ops)
- **Import** → `references/resources/Import.md` (3 ops)
- **Invitations** → `references/resources/Invitations.md` (3 ops)
- **List** → `references/resources/List.md` (3 ops)
- **OrganizationVerify** → `references/resources/OrganizationVerify.md` (3 ops)
- **Sync** → `references/resources/Sync.md` (3 ops)
- **UserVerify** → `references/resources/UserVerify.md` (3 ops)
- **SSH Key** → `references/resources/SSH-Key.md` (3 ops)
- **inference-arch** → `references/resources/inference-arch.md` (2 ops)
- **Captcha** → `references/resources/Captcha.md` (2 ops)
- **JWT** → `references/resources/JWT.md` (2 ops)
- **Namespace** → `references/resources/Namespace.md` (2 ops)
- **InternalOnly** → `references/resources/InternalOnly.md` (2 ops)
- **Stat** → `references/resources/Stat.md` (2 ops)
- **AuditLog** → `references/resources/AuditLog.md` (1 ops)
- **Federation** → `references/resources/Federation.md` (1 ops)
- **Events** → `references/resources/Events.md` (1 ops)
- **Token** → `references/resources/Token.md` (1 ops)
- **Recommendation** → `references/resources/Recommendation.md` (1 ops)
- **Telemetry** → `references/resources/Telemetry.md` (1 ops)
