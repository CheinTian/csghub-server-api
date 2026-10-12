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
├── resources/      # 106 resource index files
├── operations/     # 943 operation detail files
└── schemas/        # 688 schema groups, 696 schema files
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

- **Agent** → `references/resources/Agent.md` (73 ops)
- **Accounting** → `references/resources/Accounting.md` (65 ops)
- **Repository** → `references/resources/Repository.md` (53 ops)
- **User** → `references/resources/User.md` (48 ops)
- **Model** → `references/resources/Model.md` (43 ops)
- **Admin Asset Mirror** → `references/resources/Admin-Asset-Mirror.md` (36 ops)
- **Prompt** → `references/resources/Prompt.md` (26 ops)
- **AIGateway** → `references/resources/AIGateway.md` (22 ops)
- **Organization** → `references/resources/Organization.md` (20 ops)
- **Cluster** → `references/resources/Cluster.md` (18 ops)
- **Admin Common** → `references/resources/Admin-Common.md` (17 ops)
- **LLMService** → `references/resources/LLMService.md` (17 ops)
- **Mirror** → `references/resources/Mirror.md` (17 ops)
- **Accounting-Invoices** → `references/resources/Accounting-Invoices.md` (16 ops)
- **Admin Account Organization** → `references/resources/Admin-Account-Organization.md` (16 ops)
- **Dataset** → `references/resources/Dataset.md` (15 ops)
- **Admin Commercial API** → `references/resources/Admin-Commercial-API.md` (13 ops)
- **Admin System Config** → `references/resources/Admin-System-Config.md` (13 ops)
- **AgentCredential** → `references/resources/AgentCredential.md` (13 ops)
- **RuntimeFramework** → `references/resources/RuntimeFramework.md` (13 ops)
- **Admin Storage** → `references/resources/Admin-Storage.md` (12 ops)
- **Admin Asset Model** → `references/resources/Admin-Asset-Model.md` (11 ops)
- **Space** → `references/resources/Space.md` (11 ops)
- **License** → `references/resources/License.md` (10 ops)
- **Notifications** → `references/resources/Notifications.md` (10 ops)
- **ClawHub** → `references/resources/ClawHub.md` (9 ops)
- **Discussion** → `references/resources/Discussion.md` (9 ops)
- **Notebook** → `references/resources/Notebook.md` (9 ops)
- **Skill** → `references/resources/Skill.md` (9 ops)
- **Tag** → `references/resources/Tag.md` (9 ops)
- **Access token** → `references/resources/Access-token.md` (9 ops)
- **Code** → `references/resources/Code.md` (8 ops)
- **Collection** → `references/resources/Collection.md` (8 ops)
- **OrganizationUnit** → `references/resources/OrganizationUnit.md` (8 ops)
- **RepositoryAuthorization** → `references/resources/RepositoryAuthorization.md` (8 ops)
- **Admin Apigateway Public Inference** → `references/resources/Admin-Apigateway-Public-Inference.md` (7 ops)
- **Admin APIGateway Token Plan** → `references/resources/Admin-APIGateway-Token-Plan.md` (7 ops)
- **Admin Asset Dataset** → `references/resources/Admin-Asset-Dataset.md` (7 ops)
- **Admin Asset Sync** → `references/resources/Admin-Asset-Sync.md` (7 ops)
- **SpaceReource** → `references/resources/SpaceReource.md` (7 ops)
- **MCP** → `references/resources/MCP.md` (7 ops)
- **API Key** → `references/resources/API-Key.md` (7 ops)
- **Admin Academy Course** → `references/resources/Admin-Academy-Course.md` (6 ops)
- **Admin Account Administrator** → `references/resources/Admin-Account-Administrator.md` (6 ops)
- **Admin Accounting Compute Voucher** → `references/resources/Admin-Accounting-Compute-Voucher.md` (6 ops)
- **Admin Compute Spec** → `references/resources/Admin-Compute-Spec.md` (6 ops)
- **MCP Servers** → `references/resources/MCP-Servers.md` (6 ops)
- **Sandbox** → `references/resources/Sandbox.md` (6 ops)
- **Member** → `references/resources/Member.md` (6 ops)
- **Monitor** → `references/resources/Monitor.md` (6 ops)
- **Admin Account User** → `references/resources/Admin-Account-User.md` (5 ops)
- **Admin Asset Code** → `references/resources/Admin-Asset-Code.md` (5 ops)
- **Admin Asset MCP** → `references/resources/Admin-Asset-MCP.md` (5 ops)
- **Admin Asset Skill** → `references/resources/Admin-Asset-Skill.md` (5 ops)
- **Admin Asset Space** → `references/resources/Admin-Asset-Space.md` (5 ops)
- **Admin Compute Node** → `references/resources/Admin-Compute-Node.md` (5 ops)
- **StorageGateway** → `references/resources/StorageGateway.md` (5 ops)
- **ApiRateLimit** → `references/resources/ApiRateLimit.md` (5 ops)
- **Broadcasts** → `references/resources/Broadcasts.md` (5 ops)
- **Finetune** → `references/resources/Finetune.md` (5 ops)
- **SpaceTemplate** → `references/resources/SpaceTemplate.md` (5 ops)
- **Admin Academy Collection** → `references/resources/Admin-Academy-Collection.md` (4 ops)
- **Admin Academy User Permission** → `references/resources/Admin-Academy-User-Permission.md` (4 ops)
- **Admin Asset Resource Price** → `references/resources/Admin-Asset-Resource-Price.md` (4 ops)
- **Admin System Broadcast** → `references/resources/Admin-System-Broadcast.md` (4 ops)
- **Admin Compute Overview** → `references/resources/Admin-Compute-Overview.md` (4 ops)
- **Moderation** → `references/resources/Moderation.md` (4 ops)
- **Evaluation** → `references/resources/Evaluation.md` (4 ops)
- **OrganizationUnitMember** → `references/resources/OrganizationUnitMember.md` (4 ops)
- **SpaceSdk** → `references/resources/SpaceSdk.md` (4 ops)
- **Namespace** → `references/resources/Namespace.md` (3 ops)
- **Import** → `references/resources/Import.md` (3 ops)
- **Invitations** → `references/resources/Invitations.md` (3 ops)
- **List** → `references/resources/List.md` (3 ops)
- **OrganizationVerify** → `references/resources/OrganizationVerify.md` (3 ops)
- **Sync** → `references/resources/Sync.md` (3 ops)
- **UserVerify** → `references/resources/UserVerify.md` (3 ops)
- **SSH Key** → `references/resources/SSH-Key.md` (3 ops)
- **Admin Asset Tag** → `references/resources/Admin-Asset-Tag.md` (2 ops)
- **Admin Compute Cluster** → `references/resources/Admin-Compute-Cluster.md` (2 ops)
- **Admin Compute Instance** → `references/resources/Admin-Compute-Instance.md` (2 ops)
- **Admin compute/node** → `references/resources/Admin-compute-node.md` (2 ops)
- **inference-arch** → `references/resources/inference-arch.md` (2 ops)
- **Captcha** → `references/resources/Captcha.md` (2 ops)
- **JWT** → `references/resources/JWT.md` (2 ops)
- **InternalOnly** → `references/resources/InternalOnly.md` (2 ops)
- **Stat** → `references/resources/Stat.md` (2 ops)
- **Accounting internal** → `references/resources/Accounting-internal.md` (1 ops)
- **Admin Account Admin** → `references/resources/Admin-Account-Admin.md` (1 ops)
- **Admin accounting/consumption_report** → `references/resources/Admin-accounting-consumption-report.md` (1 ops)
- **Admin accounting/recharge_report** → `references/resources/Admin-accounting-recharge-report.md` (1 ops)
- **Admin apigateway/public_inference** → `references/resources/Admin-apigateway-public-inference.md` (1 ops)
- **Admin Asset Mcp** → `references/resources/Admin-Asset-Mcp.md` (1 ops)
- **Admin asset/resource_price** → `references/resources/Admin-asset-resource-price.md` (1 ops)
- **Admin asset/runtime_framework** → `references/resources/Admin-asset-runtime-framework.md` (1 ops)
- **AuditLog** → `references/resources/AuditLog.md` (1 ops)
- **Admin Compute Scenario** → `references/resources/Admin-Compute-Scenario.md` (1 ops)
- **Admin compute/spec** → `references/resources/Admin-compute-spec.md` (1 ops)
- **Admin marketing/eai_article** → `references/resources/Admin-marketing-eai-article.md` (1 ops)
- **Admin Marketing Email Sending** → `references/resources/Admin-Marketing-Email-Sending.md` (1 ops)
- **agent** → `references/resources/agent.md` (1 ops)
- **Federation** → `references/resources/Federation.md` (1 ops)
- **Events** → `references/resources/Events.md` (1 ops)
- **Token** → `references/resources/Token.md` (1 ops)
- **EngineArgs** → `references/resources/EngineArgs.md` (1 ops)
- **Telemetry** → `references/resources/Telemetry.md` (1 ops)
