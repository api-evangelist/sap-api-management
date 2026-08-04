# SAP API Management (sap-api-management)

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

SAP API Management is an API platform that enables organizations to design, import, publish, secure, and monitor APIs. It provides a self-service developer portal (API Business Hub Enterprise), OpenAPI-based API design tools, policy management, and access to the SAP Business Accelerator Hub for discovering and consuming SAP and partner APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sap-api-management/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sap-api-management/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Management
- Developer Portal
- Enterprise
- SAP

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### SAP API Management API

The SAP API Management API provides programmatic access to manage APIs, API products, developer portal settings, and access control through the SAP API Management platform on SAP Business Technology Platform.

- **Human URL:** [https://help.sap.com/docs/sap-api-management](https://help.sap.com/docs/sap-api-management)

#### Tags

- API Management
- Developer Portal
- SAP BTP

#### Properties

- [Documentation](https://help.sap.com/docs/sap-api-management)
- [Reference](https://api.sap.com/package/APIMgmt/overview)
- [Getting Started](https://help.sap.com/docs/sap-api-management/sap-api-management/what-is-api-management)
- [Authentication](https://help.sap.com/docs/sap-api-management/sap-api-management/user-authentication)
- [Postman Collection](collections/sap-api-management-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-api-management-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP API Management API Portal API

The SAP API Management API Portal API provides RESTful endpoints for programmatically managing API proxies, API products, applications, developers, policies, and key-value maps within the SAP API Management platform. It is used by administrators and developers to automate the full API lifecycle including creation, versioning, and publishing of APIs. The API uses OData conventions with base URL: https://{tenant-url}/apiportal/api/1.0/Management.svc.

- **Human URL:** [https://help.sap.com/docs/sap-api-management/sap-api-management/build-apis](https://help.sap.com/docs/sap-api-management/sap-api-management/build-apis)

#### Tags

- API Lifecycle
- API Portal
- API Proxy
- REST

#### Properties

- [Documentation](https://help.sap.com/docs/sap-api-management/sap-api-management/build-apis)
- [Reference](https://api.sap.com/api/APIMgmt/overview)
- [GitHub Repository](https://github.com/SAP/apibusinesshub-api-recipes)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sap-api-management/refs/heads/main/openapi/sap-api-management-portal-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sap-api-management-api-proxy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sap-api-management-api-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-api-management-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-api-management-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP API Business Hub Enterprise API

The SAP API Business Hub Enterprise (also called API Management Developer Portal) API enables programmatic management of the self-service developer portal. It supports managing API catalog content, developer registrations, application subscriptions, and portal customizations for consumer-facing API discovery and consumption.

- **Human URL:** [https://help.sap.com/docs/sap-api-management/sap-api-management/consume-apis](https://help.sap.com/docs/sap-api-management/sap-api-management/consume-apis)

#### Tags

- API Catalog
- Developer Portal
- SAP BTP
- Self Service

#### Properties

- [Documentation](https://help.sap.com/docs/sap-api-management/sap-api-management/consume-apis)
- [Reference](https://api.sap.com/api/APIMgmtDevPortal/overview)
- [Postman Collection](collections/sap-api-management-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-api-management-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP API Management Analytics API

The SAP API Management Analytics API provides access to API usage metrics, performance statistics, error rates, and traffic analytics for APIs managed on the SAP API Management platform. It supports building custom dashboards and monitoring integrations using aggregated and raw usage data.

- **Human URL:** [https://help.sap.com/docs/sap-api-management/sap-api-management/analyze-apis](https://help.sap.com/docs/sap-api-management/sap-api-management/analyze-apis)

#### Tags

- Analytics
- Metrics
- Monitoring
- Reporting

#### Properties

- [Documentation](https://help.sap.com/docs/sap-api-management/sap-api-management/analyze-apis)
- [Reference](https://api.sap.com/api/APIMgmtAnalytics/overview)
- [Postman Collection](collections/sap-api-management-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-api-management-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://api.sap.com/)
- [Documentation](https://help.sap.com/docs/sap-api-management)
- [Website](https://www.sap.com/products/technology-platform/api-management.html)
- [Getting Started](https://help.sap.com/docs/sap-api-management/sap-api-management/what-is-api-management)
- [Authentication](https://help.sap.com/docs/sap-api-management/sap-api-management/user-authentication)
- [Blog](https://blogs.sap.com/tags/73554900100700002381/)
- [Community](https://community.sap.com/topics/api-management)
- [Support](https://support.sap.com/en/product/support-by-product/73554900100700002381.html)
- [Status Page](https://www.sap.com/about/trust-center/cloud-service-status.html)
- [GitHub Organization](https://github.com/SAP-samples)
- [GitHub Repository](https://github.com/SAP/apibusinesshub-api-recipes)
- [Terms of Service](https://www.sap.com/about/agreements/policies/cloud-platform.html)
- [Privacy Policy](https://www.sap.com/about/legal/privacy.html)
- [YouTube](https://www.youtube.com/@SAPTechnology)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/sap-api-management)
- [Vocabulary](vocabulary/sap-api-management-vocabulary.yml)
- [Spectral Rules](rules/sap-api-management-rules.yml)
- [Capabilities](capabilities/api-lifecycle-management.yaml)
- [JSON-LD](json-ld/sap-api-management-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
