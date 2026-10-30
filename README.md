# Morningstar

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

Morningstar, Inc. (Nasdaq MORN) is a Chicago-based investment research and financial market data company selling fund and equity data, analyst research, ratings, indexes, and portfolio analytics to advisors, asset managers, and fintechs. Its developer portal at developer.morningstar.com documents two large API families - Direct Web Services and Dynamic Services APIs - delivered as regional REST bases (us/emea/apac-api.morningstar.com) secured with OAuth 2.0 tokens, plus a Market Data Web Services API for real-time, delayed, and end-of-day pricing, a WebSocket Streaming API for Level 1/Level 2 market data, ByAllAccounts account aggregation, and an emerging MCP/agent surface. Documentation and OpenAPI 3.x specs are fully public, but credentials are sales-gated through Morningstar onboarding - there is no self-serve signup. Morningstar remains an independent public company and owns PitchBook, DBRS (credit ratings), and ByAllAccounts.

**Areas:** Finance · Market Data · Investing · Stocks · Fund · Real-Time · Reference Data · Portfolio Analytics · Research · Index · Wealth Management · Financial Data

## Morningstar on APIs.io

Everything profiled for Morningstar is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/morningstar/](https://apis.io/providers/morningstar/)** — or go straight to one of the APIs or properties below.

### APIs (20)

- [Morningstar Market Data Web Services API](https://apis.io/apis/morningstar/morningstar-market-data-web-services-api/) — On-demand access to Morningstar's financial market data over HTTP in XML and JSON - real-time, delayed, and end-of-day pricing, price and quote, time and…
- [Morningstar Authentication API](https://apis.io/apis/morningstar/morningstar-authentication-api/) — OAuth 2.0 token issuance for all Morningstar APIs - POST /token/oauth with Basic credentials returns a bearer token valid for 60 minutes, usable against the…
- [Morningstar Time Series API](https://apis.io/apis/morningstar/morningstar-time-series-api/) — Direct Web Services time series data - historical prices, cumulative return, growth, dividend, and other calculated series for securities and managed…
- [Morningstar Screener APIs](https://apis.io/apis/morningstar/morningstar-screener-api/) — Screen global equities and managed investments (funds, ETFs) against Morningstar data points, ratings, and classifications, returning display-ready result…
- [Morningstar Investment Details APIs](https://apis.io/apis/morningstar/morningstar-investment-details-api/) — Deep security-level data for equities and managed investments - profiles, ratings, performance, holdings, fees, and hundreds of Morningstar data points - in…
- [Morningstar Investment List API](https://apis.io/apis/morningstar/morningstar-investment-list-api/) — Retrieve curated and client-defined investment lists with associated Morningstar data points for rendering list-driven experiences.
- [Morningstar Portfolio Analysis APIs](https://apis.io/apis/morningstar/morningstar-portfolio-analysis-api/) — Portfolio calculation engines as APIs - X-Ray decomposition, performance, hypothetical performance, optimizer, and the Morningstar Portfolio Risk Score -…
- [Morningstar AI Insights API](https://apis.io/apis/morningstar/morningstar-ai-insights-api/) — Asynchronous generative summaries and insights over Morningstar data and research, available in Americas and APAC/EMEA regions.
- [Morningstar Scenario Analysis API](https://apis.io/apis/morningstar/morningstar-scenario-analysis-api/) — Stress-test portfolios against historical and hypothetical market scenarios using Morningstar risk engines.
- [Morningstar Risk Profiler API](https://apis.io/apis/morningstar/morningstar-risk-profiler-api/) — Investor risk-tolerance profiling built on the FinaMetrica psychometric methodology, returning risk scores and profiles for suitability workflows.
- [Morningstar Universe API](https://apis.io/apis/morningstar/morningstar-universe-api/) — Utility API for resolving the investment universes and identifiers available to an account across Direct Web Services.
- [Morningstar Financial Planning APIs](https://apis.io/apis/morningstar/morningstar-financial-planning-apis/) — US financial-planning building blocks from the Dynamic Services APIs family - households, household members, portfolios, retirement plan lookup and…
- [Morningstar Investment Analysis APIs](https://apis.io/apis/morningstar/morningstar-investment-analysis-apis/) — Dynamic Services investment-analysis endpoints - securities data (US and global ecint), screening, autocomplete, editorial research, Investor Pulse, risk…
- [Morningstar ByAllAccounts API](https://apis.io/apis/morningstar/morningstar-byallaccounts-api/) — REST account-aggregation API from Morningstar's ByAllAccounts business, aggregating held-away investment account data for wealth platforms, also reachable…
- [Morningstar Enterprise Component APIs](https://apis.io/apis/morningstar/morningstar-enterprise-component-apis/) — APIs backing Morningstar's embeddable enterprise components - editorial and news search, security details and comparison, investment screener and…
- [Morningstar Streaming API](https://apis.io/apis/morningstar/morningstar-streaming-api/) — WebSocket-based real-time market data streaming with Level 1 quote and Level 2 market-by-price subscriptions, documented publicly through Morningstar's…
- [Morningstar Snapshot API](https://apis.io/apis/morningstar/morningstar-snapshot-api/) — On-demand Level 1 market data snapshots over HTTPS with OAuth 2.0, documented publicly through Morningstar's official .NET snapshot client library;…
- [Morningstar Agent API](https://apis.io/apis/morningstar/morningstar-agent-api/) — Morningstar's AI integration surface - the Morningstar Agent API at agents.morningstar.com plus an MCP server exposing datapoint lookup and editorial…
- [Morningstar OAUTH API](https://apis.io/apis/morningstar/morningstar-oauth-api/) — The oauth API from Morningstar — 1 operation(s) for oauth.
- [Morningstar Datapoints API](https://apis.io/apis/morningstar/morningstar-datapoints-api/) — The Datapoints API from Morningstar — 3 operation(s) for datapoints.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [morningstar](https://apis.io/servers/morningstar/morningstar/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Morningstar Agentic Access](https://apis.io/agentic-access/morningstar/morningstar-agentic-access/)

#### Collections (117)

Postman and Open Collection request collections.

- [Authorization Tokens Accounts API](https://apis.io/collections/morningstar/open-morningstar-accounts-api/)
- [Authorization Tokens Accounts Activities API](https://apis.io/collections/morningstar/open-morningstar-activities-api/)
- [Authorization Tokens Accounts Aggregates Financials API](https://apis.io/collections/morningstar/open-morningstar-aggregates-financials-api/)
- [Authorization Tokens Accounts Aggregates Market Capitalization and Enterprise Value API](https://apis.io/collections/morningstar/open-morningstar-aggregates-market-capitalization-and-enterprise-value-api/)
- [Authorization Tokens Accounts Aggregates Residual Risk and Return Sensitivity API](https://apis.io/collections/morningstar/open-morningstar-aggregates-residual-risk-and-return-sensitivity-api/)
- [Authorization Tokens Accounts Aggregates Returns API](https://apis.io/collections/morningstar/open-morningstar-aggregates-returns-api/)
- [Authorization Tokens Accounts Analyst Highlights API](https://apis.io/collections/morningstar/open-morningstar-analyst-highlights-api/)
- [Authorization Tokens Accounts Analyst Normalized Financials API](https://apis.io/collections/morningstar/open-morningstar-analyst-normalized-financials-api/)
- [Authorization Tokens Accounts attribution API](https://apis.io/collections/morningstar/open-morningstar-attribution-api/)
- [Authorization Tokens Accounts autocomplete API](https://apis.io/collections/morningstar/open-morningstar-autocomplete-api/)
- [Authorization Tokens Accounts Basic Details API](https://apis.io/collections/morningstar/open-morningstar-basic-details-api/)
- [Authorization Tokens Accounts Basic Reference API](https://apis.io/collections/morningstar/open-morningstar-basic-reference-api/)
- [Authorization Tokens Accounts BenchmarkFees API](https://apis.io/collections/morningstar/open-morningstar-benchmarkfees-api/)
- [Authorization Tokens Accounts buckets API](https://apis.io/collections/morningstar/open-morningstar-buckets-api/)
- [Authorization Tokens Accounts Clients API](https://apis.io/collections/morningstar/open-morningstar-clients-api/)
- [Authorization Tokens Accounts company entitlements API](https://apis.io/collections/morningstar/open-morningstar-company-entitlements-api/)
- [Authorization Tokens Accounts Compensation API](https://apis.io/collections/morningstar/open-morningstar-compensation-api/)
- [Authorization Tokens Accounts Consensus Estimates API](https://apis.io/collections/morningstar/open-morningstar-consensus-estimates-api/)
- [Authorization Tokens Accounts Consensus Recommendations API](https://apis.io/collections/morningstar/open-morningstar-consensus-recommendations-api/)
- [Authorization Tokens Accounts Corporate Actions API](https://apis.io/collections/morningstar/open-morningstar-corporate-actions-api/)
- [Authorization Tokens Accounts Corporate Actions Price Mergers and Acquisitions API](https://apis.io/collections/morningstar/open-morningstar-corporate-actions-price-mergers-and-acquisitions-api/)
- [Authorization Tokens Accounts Credentials API](https://apis.io/collections/morningstar/open-morningstar-credentials-api/)
- [Authorization Tokens Accounts CUSIP API](https://apis.io/collections/morningstar/open-morningstar-cusip-api/)
- [Authorization Tokens Accounts CUSIP Change API](https://apis.io/collections/morningstar/open-morningstar-cusip-change-api/)
- [Authorization Tokens Accounts custodians API](https://apis.io/collections/morningstar/open-morningstar-custodians-api/)
- …and 92 more published on APIs.io

#### Overlays (5)

OpenAPI overlays, including conversational phrasing for each operation.

- [Morningstar Agent Overlay](https://apis.io/overlays/morningstar/morningstar-agent-overlay/)
- [Morningstar Screener Overlay](https://apis.io/overlays/morningstar/morningstar-screener-overlay/)
- [Morningstar Securities Overlay](https://apis.io/overlays/morningstar/morningstar-securities-overlay/)
- [Morningstar Token Overlay](https://apis.io/overlays/morningstar/morningstar-token-overlay/)
- [Morningstar X Ray Overlay](https://apis.io/overlays/morningstar/morningstar-x-ray-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Morningstar Authentication](https://apis.io/security/morningstar/morningstar-authentication/)
- [Morningstar Domain Security](https://apis.io/security/morningstar/morningstar-domain-security/)
- [Morningstar Vulnerability Disclosure](https://apis.io/security/morningstar/morningstar-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Morningstar Scopes](https://apis.io/scopes/morningstar/morningstar-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.morningstar.com/)
- [Documentation](https://developer.morningstar.com/direct-web-services)
- [Getting started](https://developer.morningstar.com/content/documentation/documentation/get-started/authentication/get-started-authentication.md)
- [API reference](https://developer.morningstar.com/apis)
- [Support](https://www.morningstar.com/business/products/direct-web-services/contact)
- [Blog](https://www.morningstar.com/news)
- [Security](https://www.morningstar.com/company/vulnerability-disclosure)
- [Terms of service](https://www.morningstar.com/user-agreement)
- [Privacy policy](https://www.morningstar.com/company/privacy-policy)
- [GitHub](https://github.com/Morningstar)
- [Status](https://status.morningstar.com/)

## API Evangelist rating

**Kin Score 44.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 51.0 |
| Contract governance | 4.5 |
| Operational transparency | 28.9 |
| Developer ergonomics | 73.8 |
| Access clarity | 10.5 |

**Agent readiness 53.7** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | — |

**Regulatory alignment 34.3** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/morningstar/](https://apis.io/providers/morningstar/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Morningstar: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/morningstar/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
