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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Tongji University is a leading public research university in Shanghai, China (Mainland), ranked #192 in the QS World University Rankings 2025. This repository catalogs the university's public developer/API footprint as an [APIs.json](https://apis.json.org) provider profile. Tongji operates an official institutional Open Platform at `api.tongji.edu.cn` that documents a broad set of campus data and capability APIs, gated to authorized faculty and students.

APIs.json: https://raw.githubusercontent.com/api-evangelist/tongji/refs/heads/main/apis.yml

Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=tongji-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, China, Shanghai, Open Platform, Campus Data

## APIs

- **Tongji University Open Platform** — Official institutional data and capability API platform (personnel, teaching, library, one-card, research, notifications). Application/approval-gated with authorization-code/token auth, scopes, and rate limiting. Docs: https://api.tongji.edu.cn/docs

## Plans

- [plans/tongji-plans-pricing.yml](plans/tongji-plans-pricing.yml)

## Rate Limits

- [rate-limits/tongji-rate-limits.yml](rate-limits/tongji-rate-limits.yml)

## FinOps

- [finops/tongji-finops.yml](finops/tongji-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.tongji.edu.cn/
- Website (English): https://en.tongji.edu.cn/
- Developer Portal: https://api.tongji.edu.cn/docs
- LinkedIn: https://www.linkedin.com/school/tongji-university/
- Plans: plans/tongji-plans-pricing.yml
- Rate Limits: rate-limits/tongji-rate-limits.yml
- FinOps: finops/tongji-finops.yml
- Review: review.yml

## Notes

- The Open Platform documentation home (`api.tongji.edu.cn/docs`) resolves live (HTTP 200), but the APIs themselves are gated behind a faculty/student application and approval flow; no openly callable public endpoints were confirmed.
- Deep-linked documentation routes are client-side (SPA) routed and return 404 to plain HTTP probes; the `/docs` root is the canonical entry point.
- No official Tongji University GitHub organization was confirmed; none is claimed in this profile.
- No endpoints, properties, or URLs were fabricated — only resources verified during review are listed.

## Maintainers

- Kin Lane — kin@apievangelist.com
