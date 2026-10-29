# Clearstream

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

Clearstream Banking S.A. is the Deutsche Borse Group post-trade infrastructure business, providing settlement, custody, collateral management and investment-fund order routing for international securities. Its programmable surface has two layers. The incumbent layer is regulated post-trade messaging: clients connect through ClearstreamXact (Xact Web Portal, Xact File Transfer over SWIFTNet FileAct, and Xact via SWIFT FIN), CASCADE via SWIFT and MQ, Vestima for fund order routing and CmaX for triparty collateral, exchanging ISO 15022 MT and ISO 20022 MX messages whose specifications Clearstream publishes to SWIFT MyStandards, with migration to ISO 20022 driven by the SWIFT CBPR+ programme. The newer layer is a genuine REST platform at api.clearstream.com, running an OAuth 2.0 password grant hardened by mandatory mutual TLS, whose first published API is SCIM 2.0 user management for the Xact Web Portal; a free synthetic Playground API and a CmaX collateral surface are live alongside it. The OpenAPI definitions are published into the Deutsche Borse Digital Business Platform catalogue, which requires registration.

**Areas:** Capital Markets · Collateral Management · Custody · Financial Services · ISO 15022 · ISO 20022 · Post-Trade Infrastructure · Securities · Settlement · SWIFT

## Clearstream on APIs.io

Everything profiled for Clearstream is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/clearstream/](https://apis.io/providers/clearstream/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Clearstream Xact via SWIFT](https://apis.io/apis/clearstream/xact-via-swift/) — Xact via SWIFT delivers settlement, custody, asset servicing and reporting messages over the SWIFTNet FIN network. The interface uses ISO 15022 MT messages…
- [Clearstream Xact File Transfer](https://apis.io/apis/clearstream/xact-file-transfer/) — Xact File Transfer offers bulk and report-style exchange of settlement, custody, and collateral messages over SWIFTNet FileAct. Files may be delivered in…
- [Clearstream Xact Web Portal](https://apis.io/apis/clearstream/xact-web-portal/) — Xact Web Portal is the browser-based interface to ClearstreamXact for instructing settlement, custody and collateral activity, monitoring status, and…
- [Clearstream CASCADE (CSD)](https://apis.io/apis/clearstream/cascade/) — CASCADE is the German central securities depository (CSD) settlement platform. CASCADE is reachable via SWIFT FIN/FileAct messages and via MQ-based…
- [Clearstream Vestima](https://apis.io/apis/clearstream/vestima/) — Vestima is Clearstream's investment fund processing platform. It routes subscription, redemption, switch and transfer orders for mutual funds, ETFs, hedge…
- [Clearstream CmaX (Triparty Collateral)](https://apis.io/apis/clearstream/cmax/) — CmaX is Clearstream's triparty collateral management platform, automating collateral allocation, optimisation, margining and substitution across repo,…
- [Clearstream API Platform (Playground)](https://apis.io/apis/clearstream/api-platform/) — The Clearstream API Platform is the REST tier of ClearstreamXact, reachable at https://api.clearstream.com with a pre-production twin at…
- [Clearstream Xact User Management (SCIM 2.0)](https://apis.io/apis/clearstream/scim2-user-management/) — The first business API Clearstream published on its API platform: User Management (SCIM2), an implementation of the SCIM 2.0 standard for provisioning,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [clearstream-mcp.yml](https://apis.io/servers/clearstream/clearstream-mcp-yml/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Clearstream Context](https://apis.io/jsonld/clearstream/clearstream-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Clearstream API Rules](https://apis.io/rules/clearstream/clearstream-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Clearstream Authentication](https://apis.io/security/clearstream/clearstream-authentication/)
- [Clearstream Domain Security](https://apis.io/security/clearstream/clearstream-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Clearstream Scopes](https://apis.io/scopes/clearstream/clearstream-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Clearstream Plans Pricing](https://apis.io/plans/clearstream/clearstream-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Clearstream Rate Limits](https://apis.io/rate-limits/clearstream/clearstream-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Clearstream Finops](https://apis.io/finops/clearstream/clearstream-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.clearstream.com/)
- [Documentation](https://www.clearstream.com/clearstream-en/res-library/connectivity/clearstream-api-services-2916788)
- [Getting started](https://www.clearstream.com/caas/v1/media/2934048/data/3fa3fec668d8dd198e9bed4df879b26b/api-developer-guide.pdf)
- [Pricing](https://www.clearstream.com/clearstream-en/res-library/key-documents/clearstream-fee-schedule-1274812)
- [Sign up](https://www.clearstream.com/clearstream-en/about-clearstream/becoming-a-clearstream-client-1277376)
- [Support](https://www.clearstream.com/clearstream-en/about-clearstream/office-locations)
- [Blog](https://www.clearstream.com/clearstream-en/newsroom)
- [Terms of service](https://docs.developer.deutsche-boerse.com/files/DBAG_API_Platform_Terms_of_Use.pdf)
- [Privacy policy](https://www.clearstream.com/clearstream-en/privacy-notice)
- [Status](https://www.clearstream.com/clearstream-en/res-library/operational-news)

## API Evangelist rating

**Kin Score 39.0** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 6.7 |
| Contract governance | 29.5 |
| Operational transparency | 36.8 |
| Developer ergonomics | 52.4 |
| Access clarity | 44.7 |

**Agent readiness 7.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 38.0** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/clearstream/](https://apis.io/providers/clearstream/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Clearstream: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/clearstream/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
