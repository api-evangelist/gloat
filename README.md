# Gloat

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Gloat is an AI-native workforce orchestration and talent-marketplace platform. Its developer APIs let enterprises connect HR, learning, and skills data to Gloat: syncing users, jobs, projects, candidacies, and learning items, and maintaining a skills-and-job-architecture ontology (the Skills Foundation) of job families, job codes, and position titles. The platform also exposes RBAC authorization (roles, groups, permissions, access rules), certifications, applications, analytics embeds, and outbound sync webhooks. Customer APIs authenticate with a client-credentials JWT; Talent Marketplace APIs use an X-Gloat-API-Key header. All hosts are per-tenant at https://{company_slug}.gloat.com/api.

**Areas:** Company · Artificial Intelligence · Human Resources · Talent Marketplace · Skills · Workforce · Internal Mobility

## Gloat on APIs.io

Everything profiled for Gloat is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/gloat/](https://apis.io/providers/gloat/)** — or go straight to one of the APIs or properties below.

### APIs (39)

- [Gloat Customer API](https://apis.io/apis/gloat/gloat-customer-api-2/) — Tenant-scoped REST API to sync users, jobs, candidacies, projects, learning items, and the Skills Foundation job architecture into Gloat, plus RBAC…
- [Gloat Access Rules API](https://apis.io/apis/gloat/gloat-access-rules-api/) — The Access Rules API from Gloat — 2 operation(s) for access rules.
- [Gloat Admin console access API](https://apis.io/apis/gloat/gloat-admin-console-access-api/) — The Admin console access API from Gloat — 1 operation(s) for admin console access.
- [Gloat Analytics API](https://apis.io/apis/gloat/gloat-analytics-api/) — The Analytics API from Gloat — 2 operation(s) for analytics.
- [Gloat API keys API](https://apis.io/apis/gloat/gloat-api-keys-api/) — API keys management endpoints for creating, updating, and managing API keys. These endpoints require the external_api_token_management permission.
- [Gloat Applications API](https://apis.io/apis/gloat/gloat-applications-api/) — The Applications API from Gloat — 5 operation(s) for applications.
- [Gloat Auth Settings API](https://apis.io/apis/gloat/gloat-auth-settings-api/) — The auth-settings API from Gloat — 3 operation(s) for auth-settings.
- [Gloat Candidacy API](https://apis.io/apis/gloat/gloat-candidacy-api/) — Candidacies operations
- [Gloat Certifications API](https://apis.io/apis/gloat/gloat-certifications-api/) — The Certifications API from Gloat — 3 operation(s) for certifications.
- [Gloat Core Entities API](https://apis.io/apis/gloat/gloat-core-entities-api/) — The Core Entities API from Gloat — 3 operation(s) for core entities.
- [Gloat Data direct API](https://apis.io/apis/gloat/gloat-data-direct-api/) — The Data Sharing API provides endpoints for accessing and downloading your Gloat data. The API enables to retrieve lists of available file types and…
- [Gloat Groups API](https://apis.io/apis/gloat/gloat-groups-api/) — The Groups API from Gloat — 3 operation(s) for groups.
- [Gloat Integration uploads API](https://apis.io/apis/gloat/gloat-integration-uploads-api/) — Presigned HTTPS PUT URLs for uploading files to the integration (e.g. Boomi) S3 bucket under your company prefix. Requires the upload_users permission.…
- [Gloat Integrations API](https://apis.io/apis/gloat/gloat-integrations-api/) — The integrations API from Gloat — 1 operation(s) for integrations.
- [Gloat Job API](https://apis.io/apis/gloat/gloat-job-api/) — Positions/requisitions operations
- [Gloat Job Architecture > Job Code API](https://apis.io/apis/gloat/gloat-job-architecture-job-code-api/) — The Job Architecture > Job Code API from Gloat — 6 operation(s) for job architecture > job code.
- [Gloat Job Architecture > Job Code > Insights API](https://apis.io/apis/gloat/gloat-job-architecture-job-code-insights-api/) — The Job Architecture > Job Code > Insights API from Gloat — 1 operation(s) for job architecture > job code > insights.
- [Gloat Job Architecture > Job Code > Tasks API](https://apis.io/apis/gloat/gloat-job-architecture-job-code-tasks-api/) — The Job Architecture > Job Code > Tasks API from Gloat — 1 operation(s) for job architecture > job code > tasks.
- [Gloat Job Architecture > Job Family API](https://apis.io/apis/gloat/gloat-job-architecture-job-family-api/) — The Job Architecture > Job Family API from Gloat — 3 operation(s) for job architecture > job family.
- [Gloat Job Architecture > Job Function API](https://apis.io/apis/gloat/gloat-job-architecture-job-function-api/) — The Job Architecture > Job Function API from Gloat — 1 operation(s) for job architecture > job function.
- [Gloat Job Architecture > Position Title API](https://apis.io/apis/gloat/gloat-job-architecture-position-title-api/) — The Job Architecture > Position Title API from Gloat — 4 operation(s) for job architecture > position title.
- [Gloat Learning API](https://apis.io/apis/gloat/gloat-learning-api/) — The Learning API from Gloat — 1 operation(s) for learning.
- [Gloat Management Console > Ontologies API](https://apis.io/apis/gloat/gloat-management-console-ontologies-api/) — The Management Console > Ontologies API from Gloat — 3 operation(s) for management console > ontologies.
- [Gloat Meta API](https://apis.io/apis/gloat/gloat-meta-api/) — Endpoints related to service, authentication and connectivity
- [Gloat Outbound API](https://apis.io/apis/gloat/gloat-outbound-api/) — Hooks to be implemented, which Gloat can be configured to call on certain events. The payloads are defined here; the URLs are to be defined with the…
- [Gloat Permissions API](https://apis.io/apis/gloat/gloat-permissions-api/) — The Permissions API from Gloat — 2 operation(s) for permissions.
- [Gloat Projects & Projects Roles API](https://apis.io/apis/gloat/gloat-projects-projects-roles-api/) — The Projects & Projects Roles API from Gloat — 2 operation(s) for projects & projects roles.
- [Gloat RBAC Groups & Roles API](https://apis.io/apis/gloat/gloat-rbac-groups-roles-api/) — The RBAC Groups & Roles API from Gloat — 7 operation(s) for rbac groups & roles.
- [Gloat Retrieval API](https://apis.io/apis/gloat/gloat-retrieval-api/) — The Retrieval API from Gloat — 3 operation(s) for retrieval.
- [Gloat Roles API](https://apis.io/apis/gloat/gloat-roles-api/) — The Roles API from Gloat — 4 operation(s) for roles.
- [Gloat Search API](https://apis.io/apis/gloat/gloat-search-api/) — The Search API from Gloat — 2 operation(s) for search.
- [Gloat Skills API](https://apis.io/apis/gloat/gloat-skills-api/) — The Skills API from Gloat — 1 operation(s) for skills.
- [Gloat Skills foundation > File Download API](https://apis.io/apis/gloat/gloat-skills-foundation-file-download-api/) — The Skills foundation > File Download API from Gloat — 4 operation(s) for skills foundation > file download.
- [Gloat Skills Inventory > Users API](https://apis.io/apis/gloat/gloat-skills-inventory-users-api/) — The Skills Inventory > Users API from Gloat — 1 operation(s) for skills inventory > users.
- [Gloat Stats API](https://apis.io/apis/gloat/gloat-stats-api/) — The Stats API from Gloat — 1 operation(s) for stats.
- [Gloat User API](https://apis.io/apis/gloat/gloat-user-api/) — Employee operations
- [Gloat User Profile API](https://apis.io/apis/gloat/gloat-user-profile-api/) — The User Profile API from Gloat — 1 operation(s) for user profile.
- [Gloat User Skills API](https://apis.io/apis/gloat/gloat-user-skills-api/) — The User Skills API from Gloat — 1 operation(s) for user skills.
- [Gloat Users API](https://apis.io/apis/gloat/gloat-users-api/) — The Users API from Gloat — 2 operation(s) for users.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Gloat Webhooks](https://apis.io/asyncapis/gloat/gloat-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [gloat](https://apis.io/servers/gloat/gloat/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Gloat Agentic Access](https://apis.io/agentic-access/gloat/gloat-agentic-access/)

#### JSON Schema (26)

The data models the API reads and writes.

- [AccessRuleResponse](https://apis.io/schemas/gloat/gloat-access-rule-response/)
- [ApiKeyGetResponse](https://apis.io/schemas/gloat/gloat-api-key-get-response/)
- [ApiKeyRead](https://apis.io/schemas/gloat/gloat-api-key-read/)
- [ApplicationFileStatusResponse](https://apis.io/schemas/gloat/gloat-application-file-status-response/)
- [ApplicationGetSchema](https://apis.io/schemas/gloat/gloat-application-get-schema/)
- [CertificationGetData](https://apis.io/schemas/gloat/gloat-certification-get-data/)
- [GroupResponse](https://apis.io/schemas/gloat/gloat-group-response/)
- [IdentityProviderData](https://apis.io/schemas/gloat/gloat-identity-provider-data/)
- [JobCodeCreate](https://apis.io/schemas/gloat/gloat-job-code-create/)
- [JobCodeRead](https://apis.io/schemas/gloat/gloat-job-code-read/)
- [JobCodeWrite](https://apis.io/schemas/gloat/gloat-job-code-write/)
- [job_detail_object](https://apis.io/schemas/gloat/gloat-job-detail-object/)
- [job_object](https://apis.io/schemas/gloat/gloat-job-object/)
- [JobTitleRead](https://apis.io/schemas/gloat/gloat-job-title-read/)
- [JobTitleWrite](https://apis.io/schemas/gloat/gloat-job-title-write/)
- [learning_item](https://apis.io/schemas/gloat/gloat-learning-item/)
- [PaginatedAPIResponse[AccessRuleResponse]](https://apis.io/schemas/gloat/gloat-paginated-apiresponse-access-rule-response/)
- [Project](https://apis.io/schemas/gloat/gloat-project-object/)
- [project_role_object](https://apis.io/schemas/gloat/gloat-project-role-object/)
- [RoleGetResponse](https://apis.io/schemas/gloat/gloat-role-get-response/)
- [RoleRequestBody](https://apis.io/schemas/gloat/gloat-role-request-body/)
- [RoleResponse](https://apis.io/schemas/gloat/gloat-role-response/)
- [SimpleRetrievalRequest](https://apis.io/schemas/gloat/gloat-simple-retrieval-request/)
- [user_object](https://apis.io/schemas/gloat/gloat-user-object/)
- [XApiActionResult](https://apis.io/schemas/gloat/gloat-xapi-action-result/)
- …and 1 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Gloat Context](https://apis.io/jsonld/gloat/gloat-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Gloat API Rules](https://apis.io/rules/gloat/gloat-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Gloat Authentication](https://apis.io/security/gloat/gloat-authentication/)
- [Gloat Domain Security](https://apis.io/security/gloat/gloat-domain-security/)
- [Gloat Trust Center](https://apis.io/security/gloat/gloat-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.gloat.com/)
- [Documentation](https://developer.gloat.com/docs)
- [Getting started](https://developer.gloat.com/docs/using-gloat-apis)
- [API reference](https://developer.gloat.com/reference)
- [Blog](https://gloat.com/blog/)
- [Compliance](https://gloat.com/security-and-compliance/)
- [Trust centre](https://compliance.gloat.com/)
- [Terms of service](https://gloat.com/terms-of-service/)
- [Privacy policy](https://gloat.com/privacy-policy/)
- [Status](https://status.gloat.com/)

## API Evangelist rating

**Kin Score 54.5** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.4 |
| Contract quality | 70.7 |
| Contract governance | 35.6 |
| Operational transparency | 23.7 |
| Developer ergonomics | 42.3 |
| Access clarity | 36.8 |

**Agent readiness 31.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 27.3** — Employment & Payroll

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/gloat/](https://apis.io/providers/gloat/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Gloat: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/gloat/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
