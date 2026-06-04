# Tongji University (tongji)

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
