# Litmus (litmus)

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

Email testing and analytics platform that allows developers and marketers to preview, test, and analyze email campaigns across multiple email clients and devices before sending.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Developer Tools
- Email Testing
- Marketing Tools
- Quality Assurance

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Litmus Instant API

The Litmus Instant API provides REST endpoints for generating email preview screenshots across 40+ email clients by submitting HTML directly without needing to send an actual email. It is used by email editors and ESP integrations to deliver real-time rendering previews within their own platforms.

- **Human URL:** [https://docs.litmus.com/instant](https://docs.litmus.com/instant)
- **Base URL:** `https://instant-api.litmus.com/v1`

#### Tags

- Email Clients
- Email Testing
- Previews
- REST API

#### Properties

- [Documentation](https://docs.litmus.com/instant)
- [Authentication](https://docs.litmus.com/oauth-integration-guide)
- [OpenAPI](openapi/litmus-instant-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/litmus-instant.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/litmus-instant.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Litmus Legacy Previews API

The Litmus Legacy Previews API provides REST endpoints for running email preview tests, spam filter tests, link-check tests, and code analysis against submitted email HTML. Tests are initiated by POSTing to the API and results are polled until rendering is complete.

- **Human URL:** [https://docs.litmus.com/legacy-previews](https://docs.litmus.com/legacy-previews)
- **Base URL:** `https://previews-api.litmus.com/api/v1`

#### Tags

- Email Testing
- Previews
- REST API
- Spam Testing

#### Properties

- [Documentation](https://docs.litmus.com/legacy-previews)
- [OpenAPI](openapi/litmus-legacy-previews-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Litmus Email Analytics API

The Litmus Email Analytics API provides REST endpoints for retrieving email campaign engagement metrics including read rates, deletion rates, device types, email clients, geographic data, and forwarding activity. Campaign data is accessed by GUID and returns detailed activity summary reports.

- **Human URL:** [https://docs.litmus.com/email-analytics](https://docs.litmus.com/email-analytics)
- **Base URL:** `https://analytics-api.litmus.com/api/v1`

#### Tags

- Campaign Metrics
- Email Analytics
- Reporting
- REST API

#### Properties

- [Documentation](https://docs.litmus.com/email-analytics)
- [OpenAPI](openapi/litmus-email-analytics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/litmus-email-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/litmus-email-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/litmus)
- [LinkedIn](https://www.linkedin.com/company/litmus-com)
- [Website](https://www.litmus.com/)
- [Documentation](https://docs.litmus.com/)
- [Getting Started](https://www.litmus.com/getting-started/test-your-email)
- [Blog](https://www.litmus.com/blog/)
- [Community](https://litmus.com/community)
- [Authentication](https://docs.litmus.com/oauth-integration-guide)
- [Authentication](https://docs.litmus.com/oauth/web-application-flow)
- [JSON Schema](json-schema/litmus-email-test-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/litmus-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://www.litmus.com/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
