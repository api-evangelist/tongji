# Tongji University (tongji)

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

Tongji University (同济大学) is a public research university in Shanghai, China, in the national Double First-Class programme and ranked around #192 in the QS World University Rankings. This repository catalogs the university's public developer/API footprint as an [APIs.json](https://apis.json.org) provider profile.

Unlike most of the university cohort, Tongji's programmable footprint is real and it is the university's own engineering, not a vendor's. The Tongji University Information Office operates an institutional Open Platform at `api.tongji.edu.cn` — on China Education and Research Network (CERNET) address space, behind a KrakenD gateway with its own Keycloak authorization server — documenting roughly 234 interfaces across fifteen families. Thirteen reference-metadata interfaces are documented as requiring no authorization and were confirmed anonymously callable on 2026-09-01. The university also runs its own Shibboleth SAML 2.0 identity provider, federated through CARSI into eduGAIN.

APIs.json: https://raw.githubusercontent.com/api-evangelist/tongji/refs/heads/main/apis.yml

Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=tongji-api-evangelist&utm_content=repo

## Type

- University (Public Research University)
- Index
- Consumer
- 3rd-Party

## Tags

University, Higher Education, Education, China, Shanghai, Double First-Class, Open Platform, Campus Data, Identity Federation, Research Data, Library, Course Catalog, Reference Data

## Surfaces, by operator

| Surface | Operator | What it is |
|---|---|---|
| [Tongji University Open Platform](https://api.tongji.edu.cn/docs) | `institution` | The university's own campus data and capability API platform. OAuth 2.0 / OIDC via a self-run Keycloak realm, 491 published scopes, 50 req/s token-bucket rate limit, thirteen anonymously callable reference-metadata interfaces. |
| [Shibboleth Identity Provider](https://idp2.tongji.edu.cn/idp/shibboleth) | `federation` | Tongji's own SAML 2.0 IdP, registered into eduGAIN by CARSI since 2020-02-22. |
| [ROR registration](https://ror.org/03rc6as71) | `registry` | Registry membership. The ROR API is ROR's; only the membership is Tongji's. |

No `tenant` and no `vendor` surfaces were found — there is no Figshare, Pure, Ex Libris, Dataverse or Symplectic contract running under this institution's name.

## Artifacts

- OpenAPI (derived from Tongji's own documentation, split per tag): [openapi/](openapi/) — master in [openapi/_original/](openapi/_original/)
- Authentication: [authentication/tongji-open-platform-authentication.yml](authentication/tongji-open-platform-authentication.yml)
- Scopes (491, from the live OIDC discovery document): [scopes/](scopes/)
- Errors: [errors/tongji-open-platform-errors.yml](errors/tongji-open-platform-errors.yml)
- Vocabulary (13 live code tables, 730 rows): [vocabulary/tongji-open-platform-reference-metadata.yml](vocabulary/tongji-open-platform-reference-metadata.yml)
- Examples (live, unauthenticated captures): [examples/](examples/)
- JSON Schema: [json-schema/](json-schema/)
- Rules: [rules/tongji-open-platform-rules.yml](rules/tongji-open-platform-rules.yml)
- Lifecycle: [lifecycle/tongji-open-platform-lifecycle.yml](lifecycle/tongji-open-platform-lifecycle.yml)
- Conformance (education regime): [conformance/tongji-education-standards-conformance.yml](conformance/tongji-education-standards-conformance.yml)
- Identity federation: [identity-federation/](identity-federation/)
- Plans: [plans/tongji-plans-pricing.yml](plans/tongji-plans-pricing.yml)
- Rate limits: [rate-limits/tongji-rate-limits.yml](rate-limits/tongji-rate-limits.yml)
- FinOps: [finops/tongji-finops.yml](finops/tongji-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Notes

- **Correction, 2026-09-01.** The 2026-06-03 profile stated that "no openly callable public endpoints were confirmed". That was wrong. Thirteen interfaces under `/v1/metadata/` and `/v2/metadata/` are documented as 无需授权可直接访问 and every one returned HTTP 200 `application/json` to an unauthenticated GET. The June profile also missed the live OpenID Connect discovery document and the university's eduGAIN-registered Shibboleth IdP entirely.
- The deep-documentation 404s the June review recorded were an artefact of guessing SPA routes. The real routes, recovered from the rendered navigation, all resolve 200.
- Every OpenAPI in this repo is **API Evangelist's derivation** from Tongji's own published Chinese-language documentation. Tongji publishes no OpenAPI, Swagger or Postman collection of its own — `/swagger.json`, `/v3/api-docs` and `/.well-known/openapi.json` all return 404, as do `/sitemap.xml`, `/robots.txt` and `/llms.txt`.
- No institutional repository, OAI-PMH endpoint or open-data portal was found. Tongji is not a DataCite member and not a Crossref member.
- `github.com/Tongji-University` exists but is empty, unnamed and undescribed, so no GitHub organization is claimed.
- `api.tongji.edu.cn/docs/intro/other/policies` is a privacy-policy **template** the Information Office hands to campus developers, not the university's own privacy policy, and is deliberately not recorded as one.
- All documentation is Chinese-only.
- No endpoints, properties or URLs were fabricated. Every artifact carries its `method` and `source`.

## Maintainers

- Kin Lane — kin@apievangelist.com
