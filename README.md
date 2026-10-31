# Power Query

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

Power Query is Microsoft's data connectivity and transformation engine, driven by the M formula language. It ships inside Excel, Power BI Desktop, Analysis Services, Azure Data Factory and Microsoft Fabric, and reaches 300+ data sources through built-in and custom connectors built with the MIT-licensed Power Query SDK. Its programmatic surface is the Microsoft Fabric Dataflow REST API on api.fabric.microsoft.com: thirteen Swagger-documented operations that create, read, update and delete dataflows, publish and retrieve their Power Query definitions, discover their parameters, schedule execute and applyChanges jobs, and execute an M query against a dataflow on demand. Authentication is Microsoft Entra ID OAuth 2.0 with delegated Dataflow.* and Item.* scopes layered on top of Fabric workspace roles.

**Areas:** Business Intelligence · Data Integration · Data Transformation · ETL · Microsoft · Microsoft Fabric · Power BI · Dataflows · M Language · Data Connectors · Self-Service ETL

## Power Query on APIs.io

Everything profiled for Power Query is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/power-query/](https://apis.io/providers/power-query/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Power Query M Formula Language](https://apis.io/apis/power-query/m-language/) — API and language reference for the M formula language used in Power Query for data transformation expressions and custom functions.
- [Power Query Connectors API](https://apis.io/apis/power-query/connectors-api/) — API for building and managing custom data connectors for Power Query using the M language and Connector SDK.
- [Power Query Dataflows API](https://apis.io/apis/power-query/dataflows-api/) — API for managing and executing Power Query dataflows in Power Platform and Power BI for self-service ETL workflows.
- [Power Query SDK](https://apis.io/apis/power-query/sdk/) — Development toolkit for building custom Power Query connectors using Visual Studio Code, including project scaffolding, testing, and packaging of .mez…
- [Power Query Items API](https://apis.io/apis/power-query/power-query-items-api/) — The Items API from Power Query — 5 operation(s) for items.
- [Power Query Background Jobs API](https://apis.io/apis/power-query/power-query-background-jobs-api/) — The Background Jobs API from Power Query — 4 operation(s) for background jobs.
- [Power Query Query Execution API](https://apis.io/apis/power-query/power-query-query-execution-api/) — The Query Execution API from Power Query — 1 operation(s) for query execution.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Microsoft Learn MCP Server](https://apis.io/servers/power-query/microsoft-learn-mcp-server/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Power Query Context](https://apis.io/jsonld/power-query/power-query-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Power Query Vocabulary](https://apis.io/vocabularies/power-query/power-query-vocabulary/)

#### Overlays (4)

OpenAPI overlays, including conversational phrasing for each operation.

- [Power Query Background Jobs Api Phrasing Overlay](https://apis.io/overlays/power-query/power-query-background-jobs-api-phrasing-overlay/)
- [Power Query Fabric Dataflow Overlay](https://apis.io/overlays/power-query/power-query-fabric-dataflow-overlay/)
- [Power Query Items Api Phrasing Overlay](https://apis.io/overlays/power-query/power-query-items-api-phrasing-overlay/)
- [Power Query Query Execution Api Phrasing Overlay](https://apis.io/overlays/power-query/power-query-query-execution-api-phrasing-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Power Query Authentication](https://apis.io/security/power-query/power-query-authentication/)
- [Power Query Domain Security](https://apis.io/security/power-query/power-query-domain-security/)
- [Power Query Trust Center](https://apis.io/security/power-query/power-query-trust-center/)
- [Power Query Vulnerability Disclosure](https://apis.io/security/power-query/power-query-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Power Query Scopes](https://apis.io/scopes/power-query/power-query-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Power Query Plans Pricing](https://apis.io/plans/power-query/power-query-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Power Query Rate Limits](https://apis.io/rate-limits/power-query/power-query-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Power Query Finops](https://apis.io/finops/power-query/power-query-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://powerquery.microsoft.com/)
- [Documentation](https://learn.microsoft.com/en-us/power-query/)
- [Getting started](https://www.microsoft.com/en-us/power-platform/products/power-bi/getting-started-with-power-bi)
- [API reference](https://learn.microsoft.com/en-us/powerquery-m/power-query-m-function-reference)
- [Pricing](https://powerbi.microsoft.com/pricing/)
- [Support](https://powerbi.microsoft.com/en-us/support/)
- [Changelog](https://learn.microsoft.com/en-us/power-bi/fundamentals/desktop-change-log)
- [Blog](https://powerbi.microsoft.com/blog/)
- [Terms of service](https://www.microsoft.com/en-us/servicesagreement/)
- [Privacy policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub](https://github.com/microsoft)
- [Status](https://support.fabric.microsoft.com/)

## API Evangelist rating

**Kin Score 74.4** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 86.7 |
| Contract quality | 52.4 |
| Contract governance | 18.2 |
| Operational transparency | 89.5 |
| Developer ergonomics | 80.4 |
| Access clarity | 92.1 |

**Agent readiness 35.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | platform (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 43.4** — Energy & Utilities

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/power-query/](https://apis.io/providers/power-query/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Power Query: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/power-query/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
