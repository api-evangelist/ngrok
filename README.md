# ngrok (ngrok)

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

ngrok is a unified application delivery network for developers, providing secure tunnels, ingress-as-a-service, API gateway, and AI gateway capabilities. It enables developers to expose local services on the public internet, manage edge ingress, and route traffic to AI providers without redeploying applications. ngrok provides a unique URL for each tunnel, traffic policy controls, and a comprehensive REST API for programmatic management of all resources.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ngrok/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ngrok/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI Gateway
- API Gateway
- Compute
- Developer Tools
- Gateways
- Ingress
- Platform
- Proxies
- Servers
- Tunnels

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-30

## APIs

### ngrok API

The ngrok API provides programmatic access to all of ngrok's resources. The API is REST-ish, follows most REST conventions, and listens only on port 443 to avoid accidental unencrypted requests. All API access requires an API key. Resources include endpoints, tunnels, edges (HTTPS, TCP, TLS), backends, reserved domains and addresses, IP policies and restrictions, TLS and SSH certificates, event subscriptions, API keys, and credentials.

- **Human URL:** [https://ngrok.com/docs/api](https://ngrok.com/docs/api)
- **Base URL:** `https://api.ngrok.com`

#### Tags

- API Gateway
- Compute
- Demonstration
- Gateways
- Platform
- Proxies
- Servers
- Testing
- Tunnels

#### Properties

- [Documentation](https://ngrok.com/docs/api)
- [API Reference](https://ngrok.com/docs/api)
- [OpenAPI](openapi/ngrok-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ngrok-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ngrok-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/ngrok-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/tunnel.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/endpoint.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/https-edge.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tcp-edge.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tls-edge.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/reserved-domain.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/reserved-addr.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/api-key.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ip-policy.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tls-certificate.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/event-subscription.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tunnel-session.json) — [JSON Schema](https://json-schema.org/specification)
- [GitHub Repository](https://github.com/ngrok/ngrok-openapi)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/ngrok)
- [Website](https://ngrok.com)
- [Documentation](https://ngrok.com/docs)
- [API Reference](https://ngrok.com/docs/api)
- [Getting Started](https://ngrok.com/docs/getting-started)
- [Blog](https://ngrok.com/blog)
- [Changelog](https://ngrok.com/docs/changelog)
- [Pricing](https://ngrok.com/pricing)
- [Support](https://ngrok.com/support)
- [Status Page](https://status.ngrok.com)
- [GitHub Organization](https://github.com/ngrok)
- [SDK](https://github.com/ngrok/ngrok-go)
- [SDK](https://github.com/ngrok/ngrok-rust)
- [SDK](https://github.com/ngrok/ngrok-javascript)
- [SDK](https://github.com/ngrok/ngrok-python)
- [Terraform](https://registry.terraform.io/providers/ngrok/ngrok/latest)
- [Kubernetes Operator](https://github.com/ngrok/ngrok-operator)
- [X (Twitter)](https://x.com/ngrokHQ)
- [Integrations](https://ngrok.com/docs/integrations)
- [Agent Skill](https://github.com/ngrok/agent-skills)
- [L L Ms Txt](https://ngrok.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
