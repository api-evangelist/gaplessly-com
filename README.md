# Gaplessly

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

Gaplessly provides a booking system for restaurants, bars, salons, clinics and other service businesses. It offers free-to-start table reservations and appointments with zero commission and no cover fees. The platform includes a customizable brand experience, 3D floor plan visualisation, and integrations with Stripe for payments. It aims to simplify scheduling and improve customer engagement across multiple locations.

**Areas:** Company · Booking · SaaS · Restaurants · Scheduling

## Gaplessly on APIs.io

Everything profiled for Gaplessly is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/gaplessly-com/](https://apis.io/providers/gaplessly-com/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Gaplessly Agent (MCP) API](https://apis.io/apis/gaplessly-com/gaplessly-com-agent-mcp-api/) — One JSON-RPC endpoint (Model Context Protocol) an AI assistant uses to find free times at any Gaplessly business on a guest's behalf. No authentication. See…
- [Gaplessly Appointments engine API](https://apis.io/apis/gaplessly-com/gaplessly-com-appointments-engine-api/) — Read an appointments business's services, staff and appointments, and book, move or cancel appointments, with an API key. A key from a table-reservations…
- [Gaplessly Guest self-service API](https://apis.io/apis/gaplessly-com/gaplessly-com-guest-self-service-api/) — The token in a guest's booking link is the whole credential: move or cancel the booking, answer the intake form, or message the venue. One set of endpoints…
- [Gaplessly Hospitality engine API](https://apis.io/apis/gaplessly-com/gaplessly-com-hospitality-engine-api/) — Read a venue's tables, service periods and reservations, and book, change or cancel reservations, with an API key. A key from an appointments organization…
- [Gaplessly Public booking (appointments) API](https://apis.io/apis/gaplessly-com/gaplessly-com-public-booking-appointments-api/) — No authentication. Find free appointment times at a business and book one, the same calls its booking page at /book/{slug} makes.
- [Gaplessly Public booking (hospitality) API](https://apis.io/apis/gaplessly-com/gaplessly-com-public-booking-hospitality-api/) — No authentication. Find free table times and book in two steps: hold a table, then confirm it with the guest's details. An appointments business answers 404.
- [Gaplessly Shared API](https://apis.io/apis/gaplessly-com/gaplessly-com-shared-api/) — Read the organization, its clients and its free times with an API key. The same for both engines.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Gaplessly Com Webhooks](https://apis.io/asyncapis/gaplessly-com/gaplessly-com-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Gaplessly Agentic Access](https://apis.io/agentic-access/gaplessly-com/gaplessly-com-agentic-access/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Gaplessly Com Context](https://apis.io/jsonld/gaplessly-com/gaplessly-com-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Gaplessly API Rules](https://apis.io/rules/gaplessly-com/gaplessly-com-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Gaplessly Authentication](https://apis.io/security/gaplessly-com/gaplessly-com-authentication/)
- [Gaplessly Domain Security](https://apis.io/security/gaplessly-com/gaplessly-com-domain-security/)
- [Gaplessly Vulnerability Disclosure](https://apis.io/security/gaplessly-com/gaplessly-com-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Gaplessly Plans Pricing](https://apis.io/plans/gaplessly-com/gaplessly-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Gaplessly Rate Limits](https://apis.io/rate-limits/gaplessly-com/gaplessly-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://gaplessly.com/)
- [Documentation](https://gaplessly.com/docs)
- [Getting started](https://gaplessly.com/features/floor-plan-room-setup)
- [API reference](https://gaplessly.com/docs/api-reference)
- [Pricing](https://gaplessly.com/pricing)
- [Support](https://gaplessly.com/help)
- [Changelog](https://gaplessly.com/changelog)
- [Blog](https://gaplessly.com/blog)
- [Terms of service](https://gaplessly.com/legal/terms)
- [Privacy policy](https://gaplessly.com/legal/privacy)
- [Status](https://status.gaplessly.com/)

## API Evangelist rating

**Kin Score 69.9** — exemplar · rubric 0.27.0 · scored 2026-11-09

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 58.8 |
| Contract governance | 79.1 |
| Operational transparency | 76.8 |
| Developer ergonomics | 61.2 |
| Access clarity | 73.2 |

**Agent readiness 51.2** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | documented (partial credit) |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/gaplessly-com/](https://apis.io/providers/gaplessly-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Gaplessly: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/gaplessly-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
