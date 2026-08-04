# Morningstar (morningstar)

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

Morningstar, Inc. (Nasdaq MORN) is a Chicago-based investment research and financial market data company selling fund and equity data, analyst research, ratings, indexes, and portfolio analytics to advisors, asset managers, and fintechs. Its developer portal at developer.morningstar.com documents two large API families - Direct Web Services and Dynamic Services APIs - delivered as regional REST bases (us/emea/apac-api.morningstar.com) secured with OAuth 2.0 tokens, plus a Market Data Web Services API for real-time, delayed, and end-of-day pricing, a WebSocket Streaming API for Level 1/Level 2 market data, ByAllAccounts account aggregation, and an emerging MCP/agent surface. Documentation and OpenAPI 3.x specs are fully public, but credentials are sales-gated through Morningstar onboarding - there is no self-serve signup. Morningstar remains an independent public company and owns PitchBook, DBRS (credit ratings), and ByAllAccounts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/morningstar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/morningstar/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Investing
- Stocks
- Funds
- Real-Time
- Reference Data
- Portfolio Analytics
- Research
- Indexes

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

### Morningstar Market Data Web Services API

On-demand access to Morningstar's financial market data over HTTP in XML and JSON - real-time, delayed, and end-of-day pricing, price and quote, time and sales, price history, OHLCV, corporate actions, index constituents and statistics, exchange information, new and delisted listings, alerts, and search. Authentication is IP-allowlisted username/password on client-specific servers, so no public base URL is documented; streaming is offered as an add-on service.

- **Human URL:** [https://developer.morningstar.com/apis/market-data/overview](https://developer.morningstar.com/apis/market-data/overview)

### Morningstar Authentication API

OAuth 2.0 token issuance for all Morningstar APIs - POST /token/oauth with Basic credentials returns a bearer token valid for 60 minutes, usable against the regional Americas, EMEA, and APAC API bases.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/api-utilities/authentication-api/overview](https://developer.morningstar.com/direct-web-services/documentation/api-utilities/authentication-api/overview)
- **Base URL:** `https://www.us-api.morningstar.com`
- **OpenAPI:** [openapi/morningstar-dws-authentication-openapi.json](openapi/morningstar-dws-authentication-openapi.json), [openapi/morningstar-authorization-tokens-openapi.json](openapi/morningstar-authorization-tokens-openapi.json)

### Morningstar Time Series API

Direct Web Services time series data - historical prices, cumulative return, growth, dividend, and other calculated series for securities and managed investments, offered in synchronous and asynchronous request styles across regional bases.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/time-series---sync/overview](https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/time-series---sync/overview)
- **Base URL:** `https://www.us-api.morningstar.com`
- **OpenAPI:** [openapi/morningstar-dws-time-series-sync-openapi.json](openapi/morningstar-dws-time-series-sync-openapi.json), [openapi/morningstar-dws-time-series-async-openapi.json](openapi/morningstar-dws-time-series-async-openapi.json)

### Morningstar Screener APIs

Screen global equities and managed investments (funds, ETFs) against Morningstar data points, ratings, and classifications, returning display-ready result sets for advisor and investor applications.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/screener---equities/overview](https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/screener---equities/overview)
- **Base URL:** `https://www.us-api.morningstar.com`
- **OpenAPI:** [openapi/morningstar-dws-screener-equities-openapi.json](openapi/morningstar-dws-screener-equities-openapi.json), [openapi/morningstar-dws-screener-managed-investments-openapi.json](openapi/morningstar-dws-screener-managed-investments-openapi.json)

### Morningstar Investment Details APIs

Deep security-level data for equities and managed investments - profiles, ratings, performance, holdings, fees, and hundreds of Morningstar data points - in synchronous and asynchronous variants with very large published OpenAPI 3.1 contracts.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/investment-details---equities/overview](https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/investment-details---equities/overview)
- **Base URL:** `https://www.us-api.morningstar.com`
- **OpenAPI:** four specs under [openapi/](openapi/) (equities and managed investments, sync and async)

### Morningstar Investment List API

Retrieve curated and client-defined investment lists with associated Morningstar data points for rendering list-driven experiences.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/investment-list/overview](https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/investment-list/overview)
- **Base URL:** `https://www.us-api.morningstar.com`
- **OpenAPI:** [openapi/morningstar-dws-investment-list-openapi.json](openapi/morningstar-dws-investment-list-openapi.json)

### Morningstar Portfolio Analysis APIs

Portfolio calculation engines as APIs - X-Ray decomposition, performance, hypothetical performance, optimizer, and the Morningstar Portfolio Risk Score - across Direct Web Services and the US Dynamic Services portfolio-analysis endpoints.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/portfolio-x-ray/overview](https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/portfolio-x-ray/overview)
- **Base URL:** `https://www.us-api.morningstar.com`
- **OpenAPI:** seven specs under [openapi/](openapi/)

### Morningstar AI Insights API

Asynchronous generative summaries and insights over Morningstar data and research, available in Americas and APAC/EMEA regions.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/ai-insights/overview](https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/ai-insights/overview)
- **Base URL:** `https://www.us-api.morningstar.com`
- **OpenAPI:** [openapi/morningstar-dws-ai-insights-openapi.json](openapi/morningstar-dws-ai-insights-openapi.json)

### Morningstar Scenario Analysis API

Stress-test portfolios against historical and hypothetical market scenarios using Morningstar risk engines.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/scenario-analysis/overview](https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/scenario-analysis/overview)
- **Base URL:** `https://www.us-api.morningstar.com`
- **OpenAPI:** [openapi/morningstar-dws-scenario-analysis-openapi.json](openapi/morningstar-dws-scenario-analysis-openapi.json)

### Morningstar Risk Profiler API

Investor risk-tolerance profiling built on the FinaMetrica psychometric methodology, returning risk scores and profiles for suitability workflows.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/risk-profiler/overview](https://developer.morningstar.com/direct-web-services/documentation/direct-web-services/risk-profiler/overview)
- **Base URL:** `https://www.us-api.morningstar.com/risk-profiler`
- **OpenAPI:** [openapi/morningstar-dws-risk-profiler-openapi.json](openapi/morningstar-dws-risk-profiler-openapi.json), [openapi/morningstar-risk-profiler-us-openapi.json](openapi/morningstar-risk-profiler-us-openapi.json)

### Morningstar Universe API

Utility API for resolving the investment universes and identifiers available to an account across Direct Web Services.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/api-utilities/universe-api/overview](https://developer.morningstar.com/direct-web-services/documentation/api-utilities/universe-api/overview)
- **Base URL:** `https://www.us-api.morningstar.com`
- **OpenAPI:** [openapi/morningstar-dws-universe-openapi.json](openapi/morningstar-dws-universe-openapi.json)

### Morningstar Financial Planning APIs

US financial-planning building blocks from the Dynamic Services APIs family - households, household members, portfolios, retirement plan lookup and benchmark fees, statement OCR, and report retrieval/file management.

- **Human URL:** [https://developer.morningstar.com/apis/financial-planning/overview](https://developer.morningstar.com/apis/financial-planning/overview)
- **Base URL:** `https://www.us-api.morningstar.com`
- **OpenAPI:** seven specs under [openapi/](openapi/)

### Morningstar Investment Analysis APIs

Dynamic Services investment-analysis endpoints - securities data (US and global ecint), screening, autocomplete, editorial research, Investor Pulse, risk analytics, risk models, and enterprise-components usage statistics.

- **Human URL:** [https://developer.morningstar.com/apis/investment-analysis/overview](https://developer.morningstar.com/apis/investment-analysis/overview)
- **Base URL:** `https://www.us-api.morningstar.com/ec/v1`
- **OpenAPI:** ten specs under [openapi/](openapi/)

### Morningstar ByAllAccounts API

REST account-aggregation API from Morningstar's ByAllAccounts business, aggregating held-away investment account data for wealth platforms, also reachable through the us-api.morningstar.com aggapi gateway.

- **Human URL:** [https://developer.morningstar.com/apis/account-aggregation/byallaccounts/overview](https://developer.morningstar.com/apis/account-aggregation/byallaccounts/overview)
- **Base URL:** `https://www.byallaccounts.net/api/v1`
- **OpenAPI:** [openapi/morningstar-byallaccounts-openapi.json](openapi/morningstar-byallaccounts-openapi.json)

### Morningstar Enterprise Component APIs

APIs backing Morningstar's embeddable enterprise components - editorial and news search, security details and comparison, investment screener and find-similar, time series (price, dividend, growth, cumulative return), documents, cost calculator, goal analysis, and APAC/EMEA X-Ray.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/enterprise-component-apis/about](https://developer.morningstar.com/direct-web-services/documentation/enterprise-component-apis/about)
- **Base URL:** `https://www.us-api.morningstar.com/ec/v1`

### Morningstar Streaming API

WebSocket-based real-time market data streaming with Level 1 quote and Level 2 market-by-price subscriptions, documented publicly through Morningstar's official .NET streaming client library; endpoints are account-specific and provided during onboarding.

- **Human URL:** [https://github.com/Morningstar/morningstar-streaming-client](https://github.com/Morningstar/morningstar-streaming-client)

### Morningstar Snapshot API

On-demand Level 1 market data snapshots over HTTPS with OAuth 2.0, documented publicly through Morningstar's official .NET snapshot client library; endpoints are account-specific and provided during onboarding.

- **Human URL:** [https://github.com/Morningstar/morningstar-snapshot-client](https://github.com/Morningstar/morningstar-snapshot-client)

### Morningstar Agent API

Morningstar's AI integration surface - the Morningstar Agent API at agents.morningstar.com plus an MCP server exposing datapoint lookup and editorial research tools to AI agents, with a published agent design playbook.

- **Human URL:** [https://developer.morningstar.com/direct-web-services/documentation/morningstar-ai-integrations/morningstar-agent/overview](https://developer.morningstar.com/direct-web-services/documentation/morningstar-ai-integrations/morningstar-agent/overview)
- **Base URL:** `https://agents.morningstar.com`
- **OpenAPI:** [openapi/morningstar-agent-openapi.json](openapi/morningstar-agent-openapi.json)

## Common Properties

- [Website](https://www.morningstar.com/)
- [Portal](https://developer.morningstar.com)
- [Documentation](https://developer.morningstar.com/direct-web-services)
- [GitHub Organization](https://github.com/Morningstar)
- [LinkedIn](https://www.linkedin.com/company/morningstar)
- [Terms of Service](https://www.morningstar.com/user-agreement)
- [Privacy Policy](https://www.morningstar.com/company/privacy-policy)
- [Status Page](https://status.morningstar.com/)
- [Support](https://www.morningstar.com/business/products/direct-web-services/contact)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
