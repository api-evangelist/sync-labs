# Sync Labs (sync-labs)

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

Sync Labs (sync.so) provides a suite of studio-grade AI lip-sync and visual dubbing APIs. Their technology synchronizes video lip movements with any audio track using state-of-the-art models, enabling professional video dubbing, content localization, and personalized video generation at scale. Models include sync-3, lipsync-2-pro, lipsync-2, lipsync-1.9, and react-1, with support for batch processing (up to 500 videos), webhooks, Python and TypeScript SDKs, Adobe Premiere plugin, and ComfyUI integration. Backed by Y Combinator.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sync-labs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sync-labs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Artificial Intelligence
- Content Localization
- Dubbing
- Lip Sync
- Media
- Video
- Visual AI

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Sync Labs API

The Sync Labs REST API provides programmatic access to AI lip-sync and visual dubbing capabilities. Submit video and audio inputs to generate studio-grade synchronized output videos. Supports single generation, batch processing of up to 500 videos, asset management, cost estimation, and webhook notifications. Rate limited to 60 requests/min for generation endpoints.

- **Human URL:** [https://sync.so/api](https://sync.so/api)
- **Base URL:** `https://api.sync.so/v2`

#### Tags

- Artificial Intelligence
- Batch Processing
- Dubbing
- Lip Sync
- Media Processing
- Video
- Webhooks

#### Properties

- [Documentation](https://sync.so/docs/introduction)
- [OpenAPI](openapi/sync-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sync-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sync-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Pricing](https://sync.so/pricing)
- [Quickstart](https://sync.so/docs/quickstart)

### Sync Labs Python SDK

Official Python SDK for integrating the Sync Labs lip-sync API into Python applications. Supports Python 3.8+. Install via pip install syncsdk.

- **Human URL:** [https://sync.so/docs/introduction](https://sync.so/docs/introduction)

#### Tags

- Python
- SDK

#### Properties

- [Documentation](https://sync.so/docs/introduction)
- [Py P I](https://pypi.org/project/syncsdk/)
- [Postman Collection](collections/sync-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sync-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sync Labs TypeScript SDK

Official TypeScript/Node.js SDK for integrating the Sync Labs API. Supports Node.js 18+. Install via npm install @sync.so/sdk.

- **Human URL:** [https://sync.so/docs/introduction](https://sync.so/docs/introduction)

#### Tags

- JavaScript
- Node.js
- SDK
- TypeScript

#### Properties

- [Documentation](https://sync.so/docs/introduction)
- [N P M](https://www.npmjs.com/package/@sync.so/sdk)
- [Postman Collection](collections/sync-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sync-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/synchronicity-labs)
- [LinkedIn](https://www.linkedin.com/company/synclabs-ai)
- [Website](https://sync.so)
- [Documentation](https://sync.so/docs/introduction)
- [Quickstart](https://sync.so/docs/quickstart)
- [Pricing](https://sync.so/pricing)
- [A P I  Keys](https://sync.so/settings/api-keys)
- [Sign Up](https://sync.so/sign-up)
- [Contact](mailto:hello@sync.so)
- [Y  Combinator](https://www.ycombinator.com/companies/sync-2)
- [L L Ms Txt](https://sync.so/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
