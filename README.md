# Litmus (litmus)

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
