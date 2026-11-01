# Vodafone

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

Vodafone Group plc is a UK-headquartered (Newbury, England) multinational telecommunications company and one of the world's largest mobile and fixed network operators, with operations in 15 country markets and partner-market agreements covering 40+ additional countries across Europe and Africa. The group serves 279 million mobile customers, 5 million business customers, and manages 215+ million IoT connections through its Vodafone IoT platform. Beyond mobile and broadband connectivity, Vodafone operates one of the largest IoT/M2M businesses in the industry, invests in 70+ subsea cables, and runs financial services like M-PESA (Africa) and Vodapay. Through Vodafone Business it sells connectivity, cloud, security, and managed-mobility services to enterprises, and through the GSMA Open Gateway and CAMARA initiative it exposes a growing portfolio of standardised network APIs (Number Verify, SIM Swap, Quality on Demand, Device Location, Match, MVNO Discovery, and more) via the Vodafone Developer Marketplace (developer.vodafone.com), which publishes 27+ commercial and CAMARA APIs across Identity, Mobile, Analytics, Boost/QoS, and Partner categories. The Marketplace exposes sandbox and live endpoints under api-sandbox.vf-dmp.engineering.vodafone.com and api.vf-dmp.engineering.vodafone.com, with OAuth2 (Consumer Key / Consumer Secret) authentication and Postman collections for every product. Vodafone is a premier member of the CAMARA alliance hosted at the Linux Foundation, a founding participant in the GSMA Open Gateway, and one of the principal telco operators driving network-as-an-API adoption globally.

**Areas:** Telecommunications · Mobile Network Operator · 5G · 4G · Connectivity · Broadband · IoT · Open Gateway · CAMARA · Network APIs · Identity · SIM Swap

## Vodafone on APIs.io

Everything profiled for Vodafone is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/vodafone/](https://apis.io/providers/vodafone/)** — or go straight to one of the APIs or properties below.

### APIs (27)

- [Number Verification 2.0 (CAMARA)](https://apis.io/apis/vodafone/number-verification-camara/) — Frictionless mobile-number verification that confirms ownership of the MSISDN currently in use on the device, using the operator network rather than SMS…
- [Number Verification 1.0 (CAMARA)](https://apis.io/apis/vodafone/number-verification-1-camara/) — Earlier CAMARA Number Verification implementation, still maintained for backwards compatibility with integrations built before the 2.0 release.
- [SIM Swap (CAMARA)](https://apis.io/apis/vodafone/sim-swap-camara/) — CAMARA SIM Swap API that returns the timestamp of the most recent SIM change for a given MSISDN (latestSimChange), used by banks and fintech apps to detect…
- [Match (CAMARA)](https://apis.io/apis/vodafone/match-camara/) — CAMARA-aligned identity-match API that compares user-supplied attributes (name, address, date of birth) against operator-held subscriber records and returns…
- [Number Recycling (CAMARA)](https://apis.io/apis/vodafone/number-recycling-camara/) — Tells callers whether a mobile number has been recycled (re-assigned to a new subscriber) since a given date, so that downstream systems can revoke stale…
- [Quality on Demand](https://apis.io/apis/vodafone/quality-on-demand/) — CAMARA Quality on Demand API for requesting a temporary QoS uplift on a specific UE session — used for cloud gaming, live broadcast contribution, drone…
- [Quality of Service Profiles](https://apis.io/apis/vodafone/qos-profiles/) — Lists the QoS profiles a developer may request via Quality on Demand, including profile identifiers, throughput class, and latency targets.
- [QoS Provisioning](https://apis.io/apis/vodafone/qos-provisioning/) — Longer-lived QoS provisioning for enterprise customers who want a persistent QoS profile applied to a set of subscriptions. Available in DE and UK.
- [Active Subscriber](https://apis.io/apis/vodafone/active-subscriber/) — Confirms whether an MSISDN is currently an active Vodafone subscriber. Available in UK.
- [Age Verify](https://apis.io/apis/vodafone/age-verify/) — Network-based age-assurance lookup that returns whether the subscriber behind a given MSISDN is above a configured age threshold, without revealing the…
- [Call Divert](https://apis.io/apis/vodafone/call-divert/) — Indicates whether call forwarding is currently active on the target number — a useful signal for fraud-detection flows where divert-to- attacker is a common…
- [Home Network Check](https://apis.io/apis/vodafone/home-network-check/) — Returns whether a subscriber is currently on their home network or roaming — useful for fraud-scoring and conditional flows that adjust behaviour based on…
- [MVNO Discovery](https://apis.io/apis/vodafone/mvno-discovery/) — Resolves the underlying MVNO/host-network for a given mobile number so that callers can route their integration to the correct operator API endpoint.
- [Number Lookup](https://apis.io/apis/vodafone/number-lookup/) — HLR-style lookup returning the operator, country, portability status, and basic line-type metadata for a given E.164 mobile number.
- [Number Recycle](https://apis.io/apis/vodafone/number-recycle/) — Vodafone's pre-CAMARA Number Recycling lookup, retained alongside the CAMARA-aligned variant for existing integrations.
- [Tenure](https://apis.io/apis/vodafone/tenure/) — Returns how long the current subscriber has held the MSISDN — short tenure is a strong signal in fraud-scoring models for newly-acquired numbers used in…
- [Brand Registration](https://apis.io/apis/vodafone/brand-registration/) — Registers a sender brand for A2P SMS and Verified Caller flows so that consumer handsets display branded sender identity rather than a raw short-code or…
- [Verified Caller](https://apis.io/apis/vodafone/verified-caller/) — Branded-calling product that lets enterprises display a verified brand name and reason-for-call on the called party's handset. Available in UK.
- [SMS Messaging Hub](https://apis.io/apis/vodafone/sms-messaging-hub/) — A2P SMS messaging gateway for sending one-time-passcodes, alerts, and marketing messages to Vodafone subscribers and onward via interconnect.
- [Vodafone Roaming Services (VRS)](https://apis.io/apis/vodafone/roaming-services/) — Vodafone Roaming Services Network Usage Event API streams roaming network-usage events to partner operators for settlement, fraud detection, and…
- [Vodafone Analytics — Real-time Footfall](https://apis.io/apis/vodafone/analytics-realtime-footfall/) — Real-time, aggregated, and anonymised footfall counts per area derived from the Vodafone mobile network — used by retail, transport, and urban planning…
- [Vodafone Analytics — Footfall Historic Order](https://apis.io/apis/vodafone/analytics-footfall-historic-order/) — Orders historic, aggregated footfall datasets for a defined area and time window. Available in DE and UK.
- [Vodafone Analytics — Reference QuadKey Helper](https://apis.io/apis/vodafone/analytics-reference-quadkey/) — Helper API for resolving Bing-style QuadKey tile identifiers used as the spatial primary key by Vodafone Analytics Footfall products.
- [Vodafone Analytics — Free Location Dataset](https://apis.io/apis/vodafone/analytics-free-location-dataset/) — Free-tier aggregated location dataset for evaluating Vodafone Analytics before committing to paid Footfall products.
- [Block SIM](https://apis.io/apis/vodafone/block-sim/) — Partner API for blocking a SIM (e.g. lost-or-stolen) on the Vodafone network on behalf of an authenticated subscriber. Available in NL.
- [Get PUK Code](https://apis.io/apis/vodafone/get-puk-code/) — Partner API for retrieving a PUK unblocking code on behalf of an authenticated subscriber whose SIM is PIN-locked. Available in NL.
- [TMF931 — Onboarding And Ordering](https://apis.io/apis/vodafone/tmf931-onboarding-ordering/) — TM Forum TMF931 Onboarding And Ordering Open API exposed as part of the GSMA Open Gateway Operate APIs, so that aggregators and channel partners can onboard…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Vodafone Domain Security](https://apis.io/security/vodafone/vodafone-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.vodafone.com)
- [Getting started](https://developer.vodafone.com/docs/getting-started)
- [Blog](https://www.vodafone.com/news)

## API Evangelist rating

**Kin Score 14.6** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 5.3 |
| Developer ergonomics | 35.7 |
| Access clarity | 13.2 |

**Agent readiness 0.0** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
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

**Regulatory alignment 5.0** — Telecommunications

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/vodafone/](https://apis.io/providers/vodafone/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Vodafone: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/vodafone/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
