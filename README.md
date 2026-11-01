# Tongji University

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

Tongji University (同济大学) is a public research university in Shanghai, China, in the national Double First-Class programme and ranked around #192 in the QS World University Rankings. Unlike most of the university cohort, its programmable footprint is real and it is the university's own engineering, not a vendor's: the Tongji University Information Office operates an institutional Open Platform at api.tongji.edu.cn — on China Education and Research Network address space, behind a KrakenD gateway, with its own Keycloak authorization server — publishing roughly 234 documented interfaces across fifteen families covering personnel, student, teaching, research, campus-card, library, asset, procurement, education-data verification, AI and notification services. Its OpenID Connect discovery document is live and lists 491 named OAuth scopes, one per interface for most of the catalog. Thirteen reference-metadata interfaces are documented as requiring no authorization and were confirmed anonymously callable, returning live JSON code tables; everything else is gated behind a faculty or student application-and-approval process. The university also runs its own Shibboleth SAML 2.0 identity provider, registered into eduGAIN through CARSI, China's national research-and-education identity federation. What it does not have is a published contract: no OpenAPI, Swagger, Postman collection, sitemap, robots.txt, llms.txt or changelog is served anywhere on the platform, all documentation is Chinese-only, and there is no institutional repository, OAI-PMH endpoint, open-data portal, DataCite or Crossref membership. Every OpenAPI in this repo is API Evangelist's derivation from Tongji's published documentation, not a Tongji artifact.

**Areas:** University · Higher Education · Education · China · Shanghai · Double First-Class · Open Platform · Campus Data · Identity Federation · Research Data · Library · Course Catalog

## Tongji University on APIs.io

Everything profiled for Tongji University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/tongji/](https://apis.io/providers/tongji/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Tongji University Shibboleth Identity Provider (CARSI / eduGAIN)](https://apis.io/apis/tongji/identity-provider/) — Tongji University's own SAML 2.0 identity provider, registered into eduGAIN by CARSI, the CERNET Authentication and Resource Sharing Infrastructure —…
- [ROR Organization Registration](https://apis.io/apis/tongji/ror/) — Tongji University is registered in the Research Organization Registry with ROR ID https://ror.org/03rc6as71 (同济大学, Shanghai, China). This is a registry…
- [Tongji University AI Services API](https://apis.io/apis/tongji/tongji-ai-services-api/) — Asynchronous speech-recognition and document-OCR services offered to campus applications by the Tongji University Information Office.
- [Tongji University Assets and Procurement API](https://apis.io/apis/tongji/tongji-assets-and-procurement-api/) — Contract, equipment-asset and purchase-requisition records drawn from the university procurement and asset-management systems.
- [Tongji University Education Data Verification API](https://apis.io/apis/tongji/tongji-education-data-verification-api/) — Identity, qualification, degree, enrolment and insurance verification services backed by national and Shanghai municipal education data sources.
- [Tongji University Library API](https://apis.io/apis/tongji/tongji-library-api/) — Library gate-access and loan records from the Tongji University Library systems.
- [Tongji University Reference Metadata API](https://apis.io/apis/tongji/tongji-reference-metadata-api/) — Openly callable code tables (metadata dictionaries) that define the controlled vocabularies used across every other Open Platform interface.
- [Tongji University Research API](https://apis.io/apis/tongji/tongji-research-api/) — Patent, software-copyright, project, funding, award, publication and monograph records from the university research-management systems.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (3)

The data models the API reads and writes.

- [Tongji University Open Platform Response Envelope](https://apis.io/schemas/tongji/tongji-open-platform-envelope/)
- [Tongji University Open Platform Record Schemas](https://apis.io/schemas/tongji/tongji-open-platform-records/)
- [Tongji University Open Platform Reference Metadata Code Table](https://apis.io/schemas/tongji/tongji-reference-metadata-code-table/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Tongji Context](https://apis.io/jsonld/tongji/tongji-context/)

#### Examples (13)

Example requests and responses.

- [Tongji V1 Metadata Asset Campus Gate Example](https://apis.io/examples/tongji/tongji-v1-metadata-asset-campus-gate-example/)
- [Tongji V1 Metadata Meeting Meeting Room Example](https://apis.io/examples/tongji/tongji-v1-metadata-meeting-meeting-room-example/)
- [Tongji V1 Metadata Teacher Send User Types Example](https://apis.io/examples/tongji/tongji-v1-metadata-teacher-send-user-types-example/)
- [Tongji V1 Metadata Teacher Status Example](https://apis.io/examples/tongji/tongji-v1-metadata-teacher-status-example/)
- [Tongji V1 Metadata Teacher Tech Job Code Example](https://apis.io/examples/tongji/tongji-v1-metadata-teacher-tech-job-code-example/)
- [Tongji V1 Metadata Teacher Tech Job Level Code Example](https://apis.io/examples/tongji/tongji-v1-metadata-teacher-tech-job-level-code-example/)
- [Tongji V1 Metadata Teacher Tech Level Of Workers Code Example](https://apis.io/examples/tongji/tongji-v1-metadata-teacher-tech-level-of-workers-code-example/)
- [Tongji V1 Metadata Teacher Title Code Example](https://apis.io/examples/tongji/tongji-v1-metadata-teacher-title-code-example/)
- [Tongji V1 Metadata Teacher Types Example](https://apis.io/examples/tongji/tongji-v1-metadata-teacher-types-example/)
- [Tongji V1 Metadata User Person Idcard Type Example](https://apis.io/examples/tongji/tongji-v1-metadata-user-person-idcard-type-example/)
- [Tongji V1 Metadata User Sex Code Example](https://apis.io/examples/tongji/tongji-v1-metadata-user-sex-code-example/)
- [Tongji V2 Metadata Student Accom Building Code Example](https://apis.io/examples/tongji/tongji-v2-metadata-student-accom-building-code-example/)
- [Tongji V2 Metadata Student Accom Region Code Example](https://apis.io/examples/tongji/tongji-v2-metadata-student-accom-region-code-example/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Tongji University — open platform rules](https://apis.io/rules/tongji/tongji-open-platform-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Tongji Domain Security](https://apis.io/security/tongji/tongji-domain-security/)
- [Tongji Open Platform Authentication](https://apis.io/security/tongji/tongji-open-platform-authentication/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Tongji Open Platform Scopes](https://apis.io/scopes/tongji/tongji-open-platform-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Tongji Plans Pricing](https://apis.io/plans/tongji/tongji-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Tongji Rate Limits](https://apis.io/rate-limits/tongji/tongji-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Tongji Finops](https://apis.io/finops/tongji/tongji-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.tongji.edu.cn/)
- [Documentation](https://api.tongji.edu.cn/docs)
- [API reference](https://api.tongji.edu.cn/docs/interface)
- [Support](https://api.tongji.edu.cn/docs/intro/apply/contact_us)

## API Evangelist rating

**Kin Score 33.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 27.7 |
| Contract governance | 15.2 |
| Operational transparency | 31.6 |
| Developer ergonomics | 42.9 |
| Access clarity | 21.1 |

**Agent readiness 25.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/tongji/](https://apis.io/providers/tongji/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Tongji University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/tongji/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
