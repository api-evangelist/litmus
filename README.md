# Litmus (litmus)
Email testing and analytics platform that allows developers and marketers to preview, test, and analyze email campaigns across multiple email clients and devices before sending.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/litmus/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Email Testing, Marketing Tools, Quality Assurance, Developer Tools

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-03-18 

## APIs

### Litmus Instant API
The Litmus Instant API provides REST endpoints for generating email preview screenshots across 40+ email clients by submitting HTML directly without needing to send an actual email. It is used by email editors and ESP integrations to deliver real-time rendering previews within their own platforms.

**Human URL:** [https://docs.litmus.com/instant](https://docs.litmus.com/instant)


#### Tags:

 - Email Testing, Previews, REST API, Email Clients

#### Properties

- [Documentation](https://docs.litmus.com/instant)
- [Authentication](https://docs.litmus.com/oauth-integration-guide)
- [OpenAPI](openapi/litmus-instant-openapi.yml)

### Litmus Legacy Previews API
The Litmus Legacy Previews API provides REST endpoints for running email preview tests, spam filter tests, link-check tests, and code analysis against submitted email HTML. Tests are initiated by POSTing to the API and results are polled until rendering is complete.

**Human URL:** [https://docs.litmus.com/legacy-previews](https://docs.litmus.com/legacy-previews)


#### Tags:

 - Email Testing, Spam Testing, Previews, REST API

#### Properties

- [Documentation](https://docs.litmus.com/legacy-previews)
- [OpenAPI](openapi/litmus-legacy-previews-openapi.yml)

### Litmus Email Analytics API
The Litmus Email Analytics API provides REST endpoints for retrieving email campaign engagement metrics including read rates, deletion rates, device types, email clients, geographic data, and forwarding activity. Campaign data is accessed by GUID and returns detailed activity summary reports.

**Human URL:** [https://docs.litmus.com/email-analytics](https://docs.litmus.com/email-analytics)


#### Tags:

 - Email Analytics, Campaign Metrics, REST API, Reporting

#### Properties

- [Documentation](https://docs.litmus.com/email-analytics)
- [OpenAPI](openapi/litmus-email-analytics-openapi.yml)

## Common Properties

- [Website](https://www.litmus.com/)
- [Documentation](https://docs.litmus.com/)
- [Getting Started](https://www.litmus.com/getting-started/test-your-email)
- [Blog](https://www.litmus.com/blog/)
- [Community](https://litmus.com/community)
- [Authentication](https://docs.litmus.com/oauth-integration-guide)
- [Authentication](https://docs.litmus.com/oauth/web-application-flow)
- [JSONSchema](json-schema/litmus-email-test-schema.json)
- [JSON-LD](json-ld/litmus-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
