# spicrawl-com

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

Spicrawl provides a web data API that fetches, renders, and extracts any URL into clean markdown, HTML, JSON, or PDF. It supports JavaScript rendering, batch processing, login session reuse, and offers flexible output formats for AI agents and developers. The platform includes a REST endpoint at /v1/scrape, detailed documentation, SDKs, and a CLI tool, enabling developers to integrate web content extraction into applications with simple GET/POST calls. Spicrawl aims to simplify web data acquisition while handling anti-bot challenges and providing transparent credit usage.

**Areas:** Company · Web Scraping · Data Extraction · API · Automation · AI

## spicrawl-com on APIs.io

Everything profiled for spicrawl-com is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/spicrawl-com/](https://apis.io/providers/spicrawl-com/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [spicrawl-com Batch API](https://apis.io/apis/spicrawl-com/spicrawl-com-batch-api/) — Scrape many URLs as one asynchronous job.
- [spicrawl-com Browser API](https://apis.io/apis/spicrawl-com/spicrawl-com-browser-api/) — Drive a hosted browser over a DevTools Protocol (CDP) WebSocket.
- [spicrawl-com Fleet API](https://apis.io/apis/spicrawl-com/spicrawl-com-fleet-api/) — Deployment capacity and readiness.
- [spicrawl-com Health API](https://apis.io/apis/spicrawl-com/spicrawl-com-health-api/) — Liveness and readiness probes.
- [spicrawl-com Requests API](https://apis.io/apis/spicrawl-com/spicrawl-com-requests-api/) — Inspect the history of requests made in this key's project, or with the `read` scope in every project of its organization.
- [spicrawl-com Scrape API](https://apis.io/apis/spicrawl-com/spicrawl-com-scrape-api/) — Fetch, render and extract one URL synchronously.
- [spicrawl-com Sessions API](https://apis.io/apis/spicrawl-com/spicrawl-com-sessions-api/) — Reuse cookies, storage and an exit IP across requests.
- [spicrawl-com Usage API](https://apis.io/apis/spicrawl-com/spicrawl-com-usage-api/) — Credits and volume over time. Requires the `read` scope.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Spicrawl Com Agentic Access](https://apis.io/agentic-access/spicrawl-com/spicrawl-com-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [BatchCreateRequest](https://apis.io/schemas/spicrawl-com/spicrawl-com-batch-create-request/)
- [BatchJob](https://apis.io/schemas/spicrawl-com/spicrawl-com-batch-job/)
- [BatchResultLine](https://apis.io/schemas/spicrawl-com/spicrawl-com-batch-result-line/)
- [ScrapeRequest](https://apis.io/schemas/spicrawl-com/spicrawl-com-scrape-request/)
- [Session](https://apis.io/schemas/spicrawl-com/spicrawl-com-session/)
- [SessionCreateRequest](https://apis.io/schemas/spicrawl-com/spicrawl-com-session-create-request/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Spicrawl Com Context](https://apis.io/jsonld/spicrawl-com/spicrawl-com-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [spicrawl-com API Rules](https://apis.io/rules/spicrawl-com/spicrawl-com-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Spicrawl Com Authentication](https://apis.io/security/spicrawl-com/spicrawl-com-authentication/)
- [Spicrawl Com Domain Security](https://apis.io/security/spicrawl-com/spicrawl-com-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Spicrawl Com Scopes](https://apis.io/scopes/spicrawl-com/spicrawl-com-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Spicrawl Com Plans Pricing](https://apis.io/plans/spicrawl-com/spicrawl-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Spicrawl Com Rate Limits](https://apis.io/rate-limits/spicrawl-com/spicrawl-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://spicrawl.com/)
- [Documentation](https://docs.spicrawl.com/)
- [Getting started](https://docs.spicrawl.com/api-reference/introduction)
- [API reference](https://docs.spicrawl.com/api-reference/introduction)
- [Pricing](https://spicrawl.com/pricing)
- [Sign up](https://spicrawl.com/login)
- [Support](https://spicrawl.com/support)
- [Blog](https://spicrawl.com/blog)
- [Terms of service](https://spicrawl.com/terms)
- [Privacy policy](https://spicrawl.com/privacy)
- [GitHub](https://github.com/OfficialSpicrawl)

## API Evangelist rating

**Kin Score 66.5** — exemplar · rubric 0.25.0 · scored 2026-10-31

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 60.8 |
| Contract governance | 79.1 |
| Operational transparency | 33.7 |
| Developer ergonomics | 77.9 |
| Access clarity | 63.7 |

**Agent readiness 59.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 31.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/spicrawl-com/](https://apis.io/providers/spicrawl-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for spicrawl-com: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/spicrawl-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
