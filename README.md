# ngrok (ngrok)

ngrok is a unified application delivery network for developers, providing secure tunnels, ingress-as-a-service, API gateway, and AI gateway capabilities. It enables developers to expose local services on the public internet, manage edge ingress, and route traffic to AI providers without redeploying applications. ngrok provides a unique URL for each tunnel, traffic policy controls, and a comprehensive REST API for programmatic management of all resources.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ngrok/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

 - AI Gateway, API Gateway, Compute, Developer Tools, Gateways, Ingress, Platform, Proxies, Servers, Tunnels

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-28

## APIs

### ngrok API

The ngrok API provides programmatic access to all of ngrok's resources. The API is REST-ish, follows most REST conventions, and listens only on port 443 to avoid accidental unencrypted requests. All API access requires an API key. Resources include endpoints, tunnels, edges (HTTPS, TCP, TLS), backends, reserved domains and addresses, IP policies and restrictions, TLS and SSH certificates, event subscriptions, API keys, and credentials.

**Human URL:** [https://ngrok.com/docs/api](https://ngrok.com/docs/api)

**Base URL:** `https://api.ngrok.com`

#### Tags

 - API Gateway, Compute, Demonstration, Gateways, Platform, Proxies, Servers, Testing, Tunnels

#### Properties

- [Documentation](https://ngrok.com/docs/api)
- [APIReference](https://ngrok.com/docs/api)
- [OpenAPI](openapi/ngrok-api-openapi.yml)
- [JSONLD](json-ld/ngrok-context.jsonld)
- [JSONSchema - tunnel](json-schema/tunnel.json)
- [JSONSchema - endpoint](json-schema/endpoint.json)
- [JSONSchema - https-edge](json-schema/https-edge.json)
- [JSONSchema - tcp-edge](json-schema/tcp-edge.json)
- [JSONSchema - tls-edge](json-schema/tls-edge.json)
- [JSONSchema - reserved-domain](json-schema/reserved-domain.json)
- [JSONSchema - reserved-addr](json-schema/reserved-addr.json)
- [JSONSchema - api-key](json-schema/api-key.json)
- [JSONSchema - ip-policy](json-schema/ip-policy.json)
- [JSONSchema - tls-certificate](json-schema/tls-certificate.json)
- [JSONSchema - event-subscription](json-schema/event-subscription.json)
- [JSONSchema - tunnel-session](json-schema/tunnel-session.json)
- [GitHubRepository - ngrok-openapi](https://github.com/ngrok/ngrok-openapi)

## Common Properties

- [Website](https://ngrok.com)
- [Documentation](https://ngrok.com/docs)
- [APIReference](https://ngrok.com/docs/api)
- [GettingStarted](https://ngrok.com/docs/getting-started)
- [Blog](https://ngrok.com/blog)
- [ChangeLog](https://ngrok.com/docs/changelog)
- [Pricing](https://ngrok.com/pricing)
- [Support](https://ngrok.com/support)
- [StatusPage](https://status.ngrok.com)
- [GitHubOrganization](https://github.com/ngrok)
- [SDK - Go SDK](https://github.com/ngrok/ngrok-go)
- [SDK - Rust SDK](https://github.com/ngrok/ngrok-rust)
- [SDK - JavaScript SDK](https://github.com/ngrok/ngrok-javascript)
- [SDK - Python SDK](https://github.com/ngrok/ngrok-python)
- [Terraform - Terraform Provider](https://registry.terraform.io/providers/ngrok/ngrok/latest)
- [KubernetesOperator - Kubernetes Operator](https://github.com/ngrok/ngrok-operator)
- [X](https://x.com/ngrokHQ)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
