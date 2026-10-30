# ngrok

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

ngrok is a unified application delivery network for developers, providing secure tunnels, ingress-as-a-service, API gateway, and AI gateway capabilities. It enables developers to expose local services on the public internet, manage edge ingress, and route traffic to AI providers without redeploying applications. ngrok provides a unique URL for each tunnel, traffic policy controls, and a comprehensive REST API for programmatic management of all resources.

**Areas:** AI Gateway · API Gateway · Compute · Developer Tools · Gateways · Ingress · Platform · Proxies · Servers · Tunnels

## ngrok on APIs.io

Everything profiled for ngrok is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ngrok/](https://apis.io/providers/ngrok/)** — or go straight to one of the APIs or properties below.

### APIs (24)

- [ngrok Abuse Reports API](https://apis.io/apis/ngrok/ngrok-abuse-reports-api/) — Abuse Reports allow you to submit reports of abusive endpoints.
- [ngrok Agent Ingresses API](https://apis.io/apis/ngrok/ngrok-agent-ingresses-api/) — Agent Ingresses are the addresses ngrok agents connect to.
- [ngrok API Keys API](https://apis.io/apis/ngrok/ngrok-api-keys-api/) — API Keys are used to authenticate to the ngrok API.
- [ngrok Backends API](https://apis.io/apis/ngrok/ngrok-backends-api/) — Backends define how traffic is handled, including tunnel group, weighted, failover, HTTP response, and static address backends.
- [ngrok Certificate Authorities API](https://apis.io/apis/ngrok/ngrok-certificate-authorities-api/) — Certificate Authorities are x509 certificates used for mutual TLS authentication.
- [ngrok Credentials API](https://apis.io/apis/ngrok/ngrok-credentials-api/) — Tunnel Credentials are authtokens used to start ngrok tunnels.
- [ngrok Edges HTTPS API](https://apis.io/apis/ngrok/ngrok-edges-https-api/) — HTTPS Edges define HTTPS endpoints with routes and modules.
- [ngrok Edges TCP API](https://apis.io/apis/ngrok/ngrok-edges-tcp-api/) — TCP Edges define TCP endpoints for non-HTTP protocols.
- [ngrok Edges TLS API](https://apis.io/apis/ngrok/ngrok-edges-tls-api/) — TLS Edges define TLS endpoints with TLS termination and mutual TLS.
- [ngrok Endpoints API](https://apis.io/apis/ngrok/ngrok-endpoints-api/) — Endpoints represent the public URLs of active tunnels and edges.
- [ngrok Event Destinations API](https://apis.io/apis/ngrok/ngrok-event-destinations-api/) — Event Destinations define where event data is sent.
- [ngrok Event Subscriptions API](https://apis.io/apis/ngrok/ngrok-event-subscriptions-api/) — Event Subscriptions define which events trigger notifications.
- [ngrok IP Policies API](https://apis.io/apis/ngrok/ngrok-ip-policies-api/) — IP Policies contain rules to allow or deny traffic from IP ranges.
- [ngrok IP Policy Rules API](https://apis.io/apis/ngrok/ngrok-ip-policy-rules-api/) — IP Policy Rules are CIDR-based allow/deny rules within an IP Policy.
- [ngrok IP Restrictions API](https://apis.io/apis/ngrok/ngrok-ip-restrictions-api/) — IP Restrictions apply IP Policies to specific ngrok resources.
- [ngrok Reserved Addresses API](https://apis.io/apis/ngrok/ngrok-reserved-addresses-api/) — Reserved Addresses are static TCP addresses for TCP tunnels.
- [ngrok Reserved Domains API](https://apis.io/apis/ngrok/ngrok-reserved-domains-api/) — Reserved Domains are custom hostnames for HTTP/HTTPS/TLS tunnels.
- [ngrok SSH Certificate Authorities API](https://apis.io/apis/ngrok/ngrok-ssh-certificate-authorities-api/) — SSH Certificate Authorities manage keys for signing SSH certificates.
- [ngrok SSH Credentials API](https://apis.io/apis/ngrok/ngrok-ssh-credentials-api/) — SSH Credentials are public keys for authenticating SSH tunnel sessions.
- [ngrok SSH Host Certificates API](https://apis.io/apis/ngrok/ngrok-ssh-host-certificates-api/) — SSH Host Certificates authenticate ngrok tunnel servers to clients.
- [ngrok SSH User Certificates API](https://apis.io/apis/ngrok/ngrok-ssh-user-certificates-api/) — SSH User Certificates authenticate users to ngrok SSH tunnel servers.
- [ngrok TLS Certificates API](https://apis.io/apis/ngrok/ngrok-tls-certificates-api/) — TLS Certificates are x509 certificate/key pairs used to terminate TLS traffic.
- [ngrok Tunnel Sessions API](https://apis.io/apis/ngrok/ngrok-tunnel-sessions-api/) — Tunnel Sessions represent running ngrok agent connections.
- [ngrok Tunnels API](https://apis.io/apis/ngrok/ngrok-tunnels-api/) — Tunnels represent individual tunnels within a tunnel session.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Moved to /providers/ngrok/](https://apis.io/servers/ngrok/ngrok/)

#### Agent skills (1)

Agent skills built on the API.

- [expose-localhost](https://apis.io/agent-skills/ngrok/expose-localhost/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ngrok Agentic Access](https://apis.io/agentic-access/ngrok/ngrok-agentic-access/)

#### JSON Schema (12)

The data models the API reads and writes.

- [ngrok API Key](https://apis.io/schemas/ngrok/api-key/)
- [ngrok Endpoint](https://apis.io/schemas/ngrok/endpoint/)
- [ngrok Event Subscription](https://apis.io/schemas/ngrok/event-subscription/)
- [ngrok HTTPS Edge](https://apis.io/schemas/ngrok/https-edge/)
- [ngrok IP Policy](https://apis.io/schemas/ngrok/ip-policy/)
- [ngrok Reserved Address](https://apis.io/schemas/ngrok/reserved-addr/)
- [ngrok Reserved Domain](https://apis.io/schemas/ngrok/reserved-domain/)
- [ngrok TCP Edge](https://apis.io/schemas/ngrok/tcp-edge/)
- [ngrok TLS Certificate](https://apis.io/schemas/ngrok/tls-certificate/)
- [ngrok TLS Edge](https://apis.io/schemas/ngrok/tls-edge/)
- [ngrok Tunnel](https://apis.io/schemas/ngrok/tunnel/)
- [ngrok Tunnel Session](https://apis.io/schemas/ngrok/tunnel-session/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ngrok Context](https://apis.io/jsonld/ngrok/ngrok-context/)

#### Collections (49)

Postman and Open Collection request collections.

- [Ngrok Abuse Reports API](https://apis.io/collections/ngrok/open-ngrok-abuse-reports-api/)
- [Ngrok Abuse Reports Agent Ingresses API](https://apis.io/collections/ngrok/open-ngrok-agent-ingresses-api/)
- [Ngrok API](https://apis.io/collections/ngrok/open-ngrok-api/)
- [Ngrok Abuse Reports API Keys API](https://apis.io/collections/ngrok/open-ngrok-api-keys-api/)
- [Ngrok Abuse Reports Backends API](https://apis.io/collections/ngrok/open-ngrok-backends-api/)
- [Ngrok Abuse Reports Certificate Authorities API](https://apis.io/collections/ngrok/open-ngrok-certificate-authorities-api/)
- [Ngrok Abuse Reports Credentials API](https://apis.io/collections/ngrok/open-ngrok-credentials-api/)
- [Ngrok Abuse Reports Edges HTTPS API](https://apis.io/collections/ngrok/open-ngrok-edges-https-api/)
- [Ngrok Abuse Reports Edges TCP API](https://apis.io/collections/ngrok/open-ngrok-edges-tcp-api/)
- [Ngrok Abuse Reports Edges TLS API](https://apis.io/collections/ngrok/open-ngrok-edges-tls-api/)
- [Ngrok Abuse Reports Endpoints API](https://apis.io/collections/ngrok/open-ngrok-endpoints-api/)
- [Ngrok Abuse Reports Event Destinations API](https://apis.io/collections/ngrok/open-ngrok-event-destinations-api/)
- [Ngrok Abuse Reports Event Subscriptions API](https://apis.io/collections/ngrok/open-ngrok-event-subscriptions-api/)
- [Ngrok Abuse Reports IP Policies API](https://apis.io/collections/ngrok/open-ngrok-ip-policies-api/)
- [Ngrok Abuse Reports IP Policy Rules API](https://apis.io/collections/ngrok/open-ngrok-ip-policy-rules-api/)
- [Ngrok Abuse Reports IP Restrictions API](https://apis.io/collections/ngrok/open-ngrok-ip-restrictions-api/)
- [Ngrok Abuse Reports Reserved Addresses API](https://apis.io/collections/ngrok/open-ngrok-reserved-addresses-api/)
- [Ngrok Abuse Reports Reserved Domains API](https://apis.io/collections/ngrok/open-ngrok-reserved-domains-api/)
- [Ngrok Abuse Reports SSH Certificate Authorities API](https://apis.io/collections/ngrok/open-ngrok-ssh-certificate-authorities-api/)
- [Ngrok Abuse Reports SSH Credentials API](https://apis.io/collections/ngrok/open-ngrok-ssh-credentials-api/)
- [Ngrok Abuse Reports SSH Host Certificates API](https://apis.io/collections/ngrok/open-ngrok-ssh-host-certificates-api/)
- [Ngrok Abuse Reports SSH User Certificates API](https://apis.io/collections/ngrok/open-ngrok-ssh-user-certificates-api/)
- [Ngrok Abuse Reports TLS Certificates API](https://apis.io/collections/ngrok/open-ngrok-tls-certificates-api/)
- [Ngrok Abuse Reports Tunnel Sessions API](https://apis.io/collections/ngrok/open-ngrok-tunnel-sessions-api/)
- [Ngrok Abuse Reports Tunnels API](https://apis.io/collections/ngrok/open-ngrok-tunnels-api/)
- …and 24 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [ngrok — jsonschema rules](https://apis.io/rules/ngrok/ngrok-jsonschema-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Ngrok Authentication](https://apis.io/security/ngrok/ngrok-authentication/)
- [Ngrok Domain Security](https://apis.io/security/ngrok/ngrok-domain-security/)
- [Ngrok Trust Center](https://apis.io/security/ngrok/ngrok-trust-center/)
- [Ngrok Vulnerability Disclosure](https://apis.io/security/ngrok/ngrok-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ngrok Plans Pricing](https://apis.io/plans/ngrok/ngrok-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ngrok Rate Limits](https://apis.io/rate-limits/ngrok/ngrok-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ngrok Finops](https://apis.io/finops/ngrok/ngrok-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://ngrok.com)
- [Documentation](https://ngrok.com/docs)
- [Getting started](https://ngrok.com/docs/getting-started)
- [API reference](https://ngrok.com/docs/api)
- [Pricing](https://ngrok.com/pricing)
- [Support](https://ngrok.com/support)
- [Changelog](https://ngrok.com/docs/changelog)
- [Blog](https://ngrok.com/blog)
- [GitHub](https://github.com/ngrok)
- [Status](https://status.ngrok.com)

## API Evangelist rating

**Kin Score 46.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 64.0 |
| Contract governance | 9.8 |
| Operational transparency | 36.8 |
| Developer ergonomics | 71.9 |
| Access clarity | 26.3 |

**Agent readiness 31.3** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 27.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ngrok/](https://apis.io/providers/ngrok/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for ngrok: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ngrok/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
