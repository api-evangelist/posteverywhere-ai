# PostEverywhere

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

PostEverywhere provides an AI‑powered social media scheduling platform that lets users connect a wide range of AI agents such as ChatGPT, Claude, Gemini, and others to create, schedule, and publish posts across multiple social networks. The service supports bulk CSV uploads, AI‑generated captions, images and videos, and offers a visual calendar for planning content. It includes features like cross‑posting, team workspaces, approval workflows, and analytics, targeting marketers and agencies looking to automate their social media strategy.

**Areas:** Social Media · AI · Automation · Marketing · Scheduling

## PostEverywhere on APIs.io

Everything profiled for PostEverywhere is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/posteverywhere-ai/](https://apis.io/providers/posteverywhere-ai/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [PostEverywhere Accounts API](https://apis.io/apis/posteverywhere-ai/posteverywhere-ai-accounts-api/) — List and inspect connected social accounts across all 13 platforms, including per-account publish health and reconnect status.
- [PostEverywhere AI API](https://apis.io/apis/posteverywhere-ai/posteverywhere-ai-ai-api/) — Generate platform-tuned social media captions and AI images from the API, using your organization's AI credit allowance.
- [PostEverywhere Analytics API](https://apis.io/apis/posteverywhere-ai/posteverywhere-ai-analytics-api/) — Pull cross-platform performance summaries (impressions, likes, comments, and per-post results) for reporting and dashboards.
- [PostEverywhere Auth API](https://apis.io/apis/posteverywhere-ai/posteverywhere-ai-auth-api/) — Device-grant login and browser OAuth handoff: connect social accounts from CLIs, servers, and AI agents without a dashboard session.
- [PostEverywhere Campaigns API](https://apis.io/apis/posteverywhere-ai/posteverywhere-ai-campaigns-api/) — Group posts into campaigns to tag, filter, and report on related content across platforms.
- [PostEverywhere Introspection API](https://apis.io/apis/posteverywhere-ai/posteverywhere-ai-introspection-api/) — Ask the API who you are: key scopes, organization, quota, and usage. Lets SDKs, CLIs, and AI agents self-configure from a bare API key.
- [PostEverywhere Media API](https://apis.io/apis/posteverywhere-ai/posteverywhere-ai-media-api/) — Upload images, video, and PDFs (direct, presigned three-step, or imported straight from a URL), then attach them to posts on any platform.
- [PostEverywhere Platform Rules API](https://apis.io/apis/posteverywhere-ai/posteverywhere-ai-platform-rules-api/) — Per-platform composer rules (character limits, media constraints, and feature support) so clients can validate before publishing.
- [PostEverywhere Posts API](https://apis.io/apis/posteverywhere-ai/posteverywhere-ai-posts-api/) — Create, schedule, draft, retry, and inspect posts across 13 platforms: single posts, bulk batches of 50, and per-platform content overrides.
- [PostEverywhere Webhooks API](https://apis.io/apis/posteverywhere-ai/posteverywhere-ai-webhooks-api/) — Subscribe to real-time post lifecycle events (published, failed, updated) with signed deliveries and automatic retries.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Posteverywhere Ai Webhooks](https://apis.io/asyncapis/posteverywhere-ai/posteverywhere-ai-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [PostEverywhere Agentic Access](https://apis.io/agentic-access/posteverywhere-ai/posteverywhere-ai-agentic-access/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Posteverywhere Ai Context](https://apis.io/jsonld/posteverywhere-ai/posteverywhere-ai-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [PostEverywhere API Rules](https://apis.io/rules/posteverywhere-ai/posteverywhere-ai-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [PostEverywhere Authentication](https://apis.io/security/posteverywhere-ai/posteverywhere-ai-authentication/)
- [PostEverywhere Domain Security](https://apis.io/security/posteverywhere-ai/posteverywhere-ai-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [PostEverywhere Plans Pricing](https://apis.io/plans/posteverywhere-ai/posteverywhere-ai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [PostEverywhere Rate Limits](https://apis.io/rate-limits/posteverywhere-ai/posteverywhere-ai-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://posteverywhere.ai/)
- [Documentation](https://posteverywhere.ai/docs)
- [Getting started](https://posteverywhere.ai/help/getting-started/ai-assistant)
- [API reference](https://posteverywhere.ai/docs)
- [Pricing](https://posteverywhere.ai/pricing)
- [Support](https://posteverywhere.ai/contact)
- [Changelog](https://posteverywhere.ai/docs/changelog)
- [Blog](https://posteverywhere.ai/blog)
- [Terms of service](https://posteverywhere.ai/terms)
- [Privacy policy](https://posteverywhere.ai/privacy)

## API Evangelist rating

**Kin Score 61.3** — strong · rubric 0.28.0 · scored 2026-11-21

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 65.3 |
| Contract governance | 79.1 |
| Operational transparency | 47.1 |
| Developer ergonomics | 68.3 |
| Access clarity | 48.5 |

**Agent readiness 61.8** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
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
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 17.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/posteverywhere-ai/](https://apis.io/providers/posteverywhere-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for PostEverywhere: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/posteverywhere-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
