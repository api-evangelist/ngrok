# Ngrok (ngrok)
Ngrok is a service that creates secure tunnels to local servers, allowing them to be accessed remotely over the internet. This means that developers can easily test and share their web applications without having to deploy them to a public server. Ngrok provides a unique URL for each tunnel, making it simple to share the application with others for testing or demonstration purposes. Additionally, Ngrok offers features such as TCP tunneling, custom headers, and password protection to ensure secure and customizable remote access to local servers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ngrok/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Gateways, Compute, Tunnels, Servers, Testing, Demonstration, Platform, Proxies

## Timestamps

- **Created:** 2025-01-08 
- **Modified:** 2026-03-16 

## APIs

### Ngrok API
The ngrok API provides programmatic access to all of ngrok's resources. The API is REST-ish. It follows most of the conventions of a REST API but diverges slightly when the REST model does not fit well. The API listens only on port 443 to help avoid any accidental unencrypted requests. All API access requires an API key. Resources include endpoints, tunnels, edges (HTTPS, TCP, TLS), backends, reserved domains and addresses, IP policies and restrictions, TLS and SSH certificates, event subscriptions, API keys, and credentials.

**Human URL:** [https://ngrok.com/docs/api](https://ngrok.com/docs/api)


#### Tags:

 - Gateways, Compute, Tunnels, Servers, Testing, Demonstration, Platform, Proxies

#### Properties

- [Documentation](https://ngrok.com/docs/api)
- [OpenAPI](openapi/ngrok-api-openapi.yml)
- [JSONSchema](json-schema/tunnel.json)
- [JSONSchema](json-schema/endpoint.json)
- [JSONSchema](json-schema/https-edge.json)
- [JSONSchema](json-schema/tcp-edge.json)
- [JSONSchema](json-schema/tls-edge.json)
- [JSONSchema](json-schema/reserved-domain.json)
- [JSONSchema](json-schema/reserved-addr.json)
- [JSONSchema](json-schema/api-key.json)
- [JSONSchema](json-schema/ip-policy.json)
- [JSONSchema](json-schema/tls-certificate.json)
- [JSONSchema](json-schema/event-subscription.json)
- [JSONSchema](json-schema/tunnel-session.json)
- [JSONLD](json-ld/ngrok-context.jsonld)

## Common Properties

- [Documentation](https://ngrok.com/docs)
- [Blog](https://ngrok.com/blog)
- [Documentation](https://ngrok.com/docs/api)
- [GitHubOrg](https://github.com/ngrok)
- [Pricing](https://ngrok.com/pricing)
- [Support](https://ngrok.com/support)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
