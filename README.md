# Lenskart

Lenskart is a direct-to-consumer eyewear company operating an omnichannel retail business across prescription eyeglasses, sunglasses, contact lenses and eye-care services. It sells through localized storefronts (India, United States, Singapore and other markets) and mobile apps, and merchandises its own house brands including Vincent Chase, John Jacobs, Lenskart Studio and Lenskart Boost alongside third-party labels.

Backed by: softbank-vision-fund

## API surface

As of the 2026-07-19 enrichment pass, **Lenskart publishes no public API**. No developer portal, API reference, OpenAPI/AsyncAPI definition, webhook catalog, MCP server or client SDK could be verified.

- `developer.lenskart.com` and `docs.lenskart.com` resolve but are gated behind Cloudflare (HTTP 403 unauthenticated) — neither can be confirmed as a public developer surface.
- `api.lenskart.com` resolves and terminates TLS 1.3 but returns HTTP 404 at the root.
- No `/.well-known/` discovery documents are published; the storefront soft-404s every `/.well-known/` path into its single-page app.
- No first-party SDKs were found on npm, PyPI or the other public registries, and no substantive public GitHub organization exists.

## Artifacts

- `security/lenskart-domain-security.yml` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC posture.
- `well-known/lenskart-well-known.yml` — recorded result of the `/.well-known/` sweep (none published).
- `llms/lenskart-llms.txt` — generated llms.txt for the company surface.
