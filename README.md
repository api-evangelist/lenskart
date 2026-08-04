# Lenskart

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
