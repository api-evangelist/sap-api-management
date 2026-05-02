# SAP API Management

SAP API Management is an API platform that enables organizations to design, import, publish, secure, and monitor APIs. It provides a self-service developer portal (API Business Hub Enterprise), OpenAPI-based API design tools, policy management, and access to the SAP Business Accelerator Hub for discovering and consuming SAP and partner APIs.

## APIs

### SAP API Management API
Provides programmatic access to manage APIs, API products, developer portal settings, and access control through the SAP API Management platform on SAP Business Technology Platform.

- [Documentation](https://help.sap.com/docs/sap-api-management)
- [Reference](https://api.sap.com/package/APIMgmt/overview)

### SAP API Management API Portal API
RESTful endpoints (OData) for programmatically managing API proxies, products, applications, developers, policies, and key-value maps. Supports the full API lifecycle including CI/CD automation.

- [Documentation](https://help.sap.com/docs/sap-api-management/sap-api-management/build-apis)
- [OpenAPI](openapi/sap-api-management-portal-openapi.yml)
- [GitHub Recipes](https://github.com/SAP/apibusinesshub-api-recipes)

### SAP API Business Hub Enterprise API
Enables programmatic management of the self-service developer portal including API catalog, developer registrations, and application subscriptions.

- [Documentation](https://help.sap.com/docs/sap-api-management/sap-api-management/consume-apis)
- [Reference](https://api.sap.com/api/APIMgmtDevPortal/overview)

### SAP API Management Analytics API
Access to API usage metrics, performance statistics, error rates, and traffic analytics for building custom dashboards.

- [Documentation](https://help.sap.com/docs/sap-api-management/sap-api-management/analyze-apis)
- [Reference](https://api.sap.com/api/APIMgmtAnalytics/overview)

## Properties

| Type | URL |
|------|-----|
| Website | https://www.sap.com/products/technology-platform/api-management.html |
| Portal | https://api.sap.com/ |
| Documentation | https://help.sap.com/docs/sap-api-management |
| Authentication | https://help.sap.com/docs/sap-api-management/sap-api-management/user-authentication |
| GitHub Organization | https://github.com/SAP-samples |
| Community | https://community.sap.com/topics/api-management |
| Blog | https://blogs.sap.com/tags/73554900100700002381/ |
| Support | https://support.sap.com/en/product/support-by-product/73554900100700002381.html |
| Stack Overflow | https://stackoverflow.com/questions/tagged/sap-api-management |

## Artifacts

### OpenAPI Specifications
| Spec | Description |
|------|-------------|
| [API Portal OpenAPI](openapi/sap-api-management-portal-openapi.yml) | API proxy, product, provider, and application management |

### Capabilities
| Capability | Description |
|------------|-------------|
| [API Lifecycle Management](capabilities/api-lifecycle-management.yaml) | Unified API proxy and product lifecycle workflows |

### Shared Capabilities
| Capability | Description |
|------------|-------------|
| [API Portal](capabilities/shared/api-portal.yaml) | API Portal OData management service consumed definition |

### Schemas
| Schema | Description |
|--------|-------------|
| [API Proxy Schema](json-schema/sap-api-management-api-proxy-schema.json) | API proxy data model |
| [API Product Schema](json-schema/sap-api-management-api-product-schema.json) | API product data model |

### Other Artifacts
| Artifact | Description |
|----------|-------------|
| [API Proxy Structure](json-structure/sap-api-management-api-proxy-structure.json) | API proxy field documentation |
| [JSON-LD Context](json-ld/sap-api-management-context.jsonld) | Linked data context for SAP API Management concepts |
| [Vocabulary](vocabulary/sap-api-management-vocabulary.yml) | API management and SAP BTP domain vocabulary |
| [Rules](rules/sap-api-management-rules.yml) | Spectral ruleset for API governance |

### Examples
| Example | Description |
|---------|-------------|
| [List API Proxies](examples/sap-api-management-list-api-proxies-example.json) | API proxy list request/response |
| [Create API Product](examples/sap-api-management-create-api-product-example.json) | API product creation request/response |
