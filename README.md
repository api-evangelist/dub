# Dub (dub)

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

Dub is the open-source link attribution platform for short links, conversion tracking, and affiliate programs. It provides a REST API for creating and managing short links, tracking analytics and conversion events (clicks, leads, and sales), managing workspaces and custom domains, and building affiliate partner programs. Dub powers over 100 million clicks and 2 million links monthly for marketing teams at companies including Vercel, Perplexity, Twilio, Buffer, and Framer.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/dub/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dub/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=dub-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=dub-api-evangelist&utm_content=repo)

## Tags

- Link Management
- URL Shortener
- Analytics
- Conversion Tracking
- Affiliate Programs
- Open Source

## APIs

| API | Description | Docs |
|-----|-------------|------|
| Dub Links API | Create, retrieve, update, and delete short links with custom domains, UTM parameters, deep links, cloaking, expiration, and geo targeting | [Docs](https://dub.co/docs/api-reference/introduction) |
| Dub Analytics API | Retrieve analytics and event data including click counts, conversion events, geographic breakdowns, device info, and referrer tracking | [Docs](https://dub.co/docs/api-reference/introduction) |
| Dub Partners API | Create and manage affiliate partners, groups, tags, payouts, and advanced reward structures | [Docs](https://dub.co/docs/api-reference/introduction) |
| Dub Domains API | List and manage custom domains with SSL certificate provisioning | [Docs](https://dub.co/docs/api-reference/introduction) |

## Plans / Rate Limits / FinOps

- [Plans & Pricing](plans/dub-plans-pricing.yml) — Free, Pro ($25/mo), Business ($75/mo), Advanced ($250/mo), Enterprise (custom)
- [Rate Limits](rate-limits/dub-rate-limits.yml) — 60–3,000 req/min depending on plan; 429 on breach; IETF rate limit headers
- [FinOps](finops/dub-finops.yml) — FOCUS-aligned cost tracking for links, events, API requests, and partner payouts

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://dub.co |
| Documentation | https://dub.co/docs |
| API Reference | https://dub.co/docs/api-reference/introduction |
| GitHub Organization | https://github.com/dubinc |
| LinkedIn | https://www.linkedin.com/company/dubinc |
| X / Twitter | https://x.com/dubdotco |
| Blog | https://dub.co/blog |
| Changelog | https://dub.co/changelog |
| Pricing | https://dub.co/pricing |
| Status Page | https://status.dub.co |
| TypeScript SDK | https://github.com/dubinc/dub-ts |
| Python SDK | https://github.com/dubinc/dub-python |
| Go SDK | https://github.com/dubinc/dub-go |
| Ruby SDK | https://github.com/dubinc/dub-ruby |
| PHP SDK | https://github.com/dubinc/dub-php |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
