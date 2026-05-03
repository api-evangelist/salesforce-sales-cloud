# Salesforce Sales Cloud

Enterprise CRM platform providing sales automation, customer relationship management, and business intelligence capabilities through REST and SOAP APIs.

**URL:** https://www.salesforce.com/products/sales-cloud/overview/

**Tags:** Cloud, CRM, Customer Management, Enterprise, Sales

## APIs

### Salesforce REST API
- **OpenAPI:** [salesforce-sales-cloud-rest-api-openapi.yml](openapi/salesforce-sales-cloud-rest-api-openapi.yml)
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/

### Bulk API 2.0
- **OpenAPI:** [salesforce-sales-cloud-bulk-api-openapi.yml](openapi/salesforce-sales-cloud-bulk-api-openapi.yml)
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/

### Analytics REST API
- **OpenAPI:** [salesforce-sales-cloud-analytics-api-openapi.yml](openapi/salesforce-sales-cloud-analytics-api-openapi.yml)
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/

### Platform Events API
- **OpenAPI:** [salesforce-sales-cloud-platform-events-api-openapi.yml](openapi/salesforce-sales-cloud-platform-events-api-openapi.yml)
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/

### Salesforce Composite API
- **OpenAPI:** [salesforce-sales-cloud-composite-api-openapi.yml](openapi/salesforce-sales-cloud-composite-api-openapi.yml)
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/using_composite_resources.htm

### Salesforce Connect REST API
- **OpenAPI:** [salesforce-sales-cloud-connect-api-openapi.yml](openapi/salesforce-sales-cloud-connect-api-openapi.yml)
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/

### Salesforce GraphQL API
- **OpenAPI:** [salesforce-sales-cloud-graphql-api-openapi.yml](openapi/salesforce-sales-cloud-graphql-api-openapi.yml)
- **Documentation:** https://developer.salesforce.com/docs/platform/graphql/overview

### Salesforce Tooling API
- **OpenAPI:** [salesforce-sales-cloud-tooling-api-openapi.yml](openapi/salesforce-sales-cloud-tooling-api-openapi.yml)
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/

### Salesforce User Interface API
- **OpenAPI:** [salesforce-sales-cloud-ui-api-openapi.yml](openapi/salesforce-sales-cloud-ui-api-openapi.yml)
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/

### Salesforce Apex REST API
- **OpenAPI:** [salesforce-sales-cloud-apex-rest-api-openapi.yml](openapi/salesforce-sales-cloud-apex-rest-api-openapi.yml)
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm

### Salesforce Change Data Capture API
- **OpenAPI:** [salesforce-sales-cloud-change-data-capture-api-openapi.yml](openapi/salesforce-sales-cloud-change-data-capture-api-openapi.yml)
- **Documentation:** https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/

## Common Resources

| Type | URL |
|------|-----|
| Portal | https://developer.salesforce.com/ |
| Authentication | https://help.salesforce.com/s/articleView?id=sf.remoteaccess_authenticate.htm |
| API Console | https://workbench.developerforce.com/ |
| Status | https://status.salesforce.com/ |
| SDKs | https://developer.salesforce.com/tools/sdk |
| Trailhead Learning | https://trailhead.salesforce.com/en/content/learn/modules/api_basics |
| API Limits | https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm |
| Terms of Service | https://www.salesforce.com/company/legal/agreements/ |
| Privacy Policy | https://www.salesforce.com/company/privacy/ |
| Postman Collection | https://www.postman.com/salesforce-developers/workspace/salesforce-developers |

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [salesforce-sales-cloud-rest-api-openapi.yml](openapi/salesforce-sales-cloud-rest-api-openapi.yml) | Core REST API — sObjects, SOQL, SOSL, approvals |
| [salesforce-sales-cloud-bulk-api-openapi.yml](openapi/salesforce-sales-cloud-bulk-api-openapi.yml) | Bulk API 2.0 — large dataset operations |
| [salesforce-sales-cloud-analytics-api-openapi.yml](openapi/salesforce-sales-cloud-analytics-api-openapi.yml) | Analytics API — reports and dashboards |
| [salesforce-sales-cloud-platform-events-api-openapi.yml](openapi/salesforce-sales-cloud-platform-events-api-openapi.yml) | Platform Events API — event publishing |
| [salesforce-sales-cloud-composite-api-openapi.yml](openapi/salesforce-sales-cloud-composite-api-openapi.yml) | Composite API — batched requests |
| [salesforce-sales-cloud-connect-api-openapi.yml](openapi/salesforce-sales-cloud-connect-api-openapi.yml) | Connect REST API — Chatter and collaboration |
| [salesforce-sales-cloud-graphql-api-openapi.yml](openapi/salesforce-sales-cloud-graphql-api-openapi.yml) | GraphQL API — flexible data queries |
| [salesforce-sales-cloud-tooling-api-openapi.yml](openapi/salesforce-sales-cloud-tooling-api-openapi.yml) | Tooling API — development tools |
| [salesforce-sales-cloud-ui-api-openapi.yml](openapi/salesforce-sales-cloud-ui-api-openapi.yml) | UI API — Lightning-aware UI data |
| [salesforce-sales-cloud-apex-rest-api-openapi.yml](openapi/salesforce-sales-cloud-apex-rest-api-openapi.yml) | Apex REST API — custom endpoints |
| [salesforce-sales-cloud-change-data-capture-api-openapi.yml](openapi/salesforce-sales-cloud-change-data-capture-api-openapi.yml) | Change Data Capture API |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [salesforce-sales-cloud-rules.yml](rules/salesforce-sales-cloud-rules.yml) | Spectral rules enforcing Salesforce Sales Cloud API conventions |

### Capabilities

| Capability | Description |
|------------|-------------|
| [sales-pipeline-management.yaml](capabilities/sales-pipeline-management.yaml) | Sales pipeline management — accounts, contacts, leads, opportunities, analytics (16 tools) |
| [data-integration.yaml](capabilities/data-integration.yaml) | Data integration — bulk loading, SOQL extraction, job management (8 tools) |

**Shared Definitions:**

| Shared | Description |
|--------|-------------|
| [sales-cloud-rest-api.yaml](capabilities/shared/sales-cloud-rest-api.yaml) | Core REST API consumed definition |
| [sales-cloud-analytics-api.yaml](capabilities/shared/sales-cloud-analytics-api.yaml) | Analytics API consumed definition |
| [sales-cloud-bulk-api.yaml](capabilities/shared/sales-cloud-bulk-api.yaml) | Bulk API 2.0 consumed definition |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [salesforce-sales-cloud-account-schema.json](json-schema/salesforce-sales-cloud-account-schema.json) | Account record schema |
| [salesforce-sales-cloud-contact-schema.json](json-schema/salesforce-sales-cloud-contact-schema.json) | Contact record schema |
| [salesforce-sales-cloud-lead-schema.json](json-schema/salesforce-sales-cloud-lead-schema.json) | Lead record schema |
| [salesforce-sales-cloud-opportunity-schema.json](json-schema/salesforce-sales-cloud-opportunity-schema.json) | Opportunity record schema |
| [salesforce-sales-cloud-task-schema.json](json-schema/salesforce-sales-cloud-task-schema.json) | Task record schema |
| [salesforce-sales-cloud-case-schema.json](json-schema/salesforce-sales-cloud-case-schema.json) | Case record schema |
| [salesforce-sales-cloud-campaign-schema.json](json-schema/salesforce-sales-cloud-campaign-schema.json) | Campaign record schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [salesforce-sales-cloud-account-structure.json](json-structure/salesforce-sales-cloud-account-structure.json) | Account sObject field documentation |
| [salesforce-sales-cloud-opportunity-structure.json](json-structure/salesforce-sales-cloud-opportunity-structure.json) | Opportunity sObject field documentation |

### JSON-LD Context

| Context | Description |
|---------|-------------|
| [salesforce-sales-cloud-context.jsonld](json-ld/salesforce-sales-cloud-context.jsonld) | JSON-LD context for Salesforce CRM entities |

### Examples

| Example | Description |
|---------|-------------|
| [salesforce-sales-cloud-create-opportunity-example.json](examples/salesforce-sales-cloud-create-opportunity-example.json) | Create Opportunity request/response |
| [salesforce-sales-cloud-soql-query-example.json](examples/salesforce-sales-cloud-soql-query-example.json) | SOQL query for open opportunities |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [salesforce-sales-cloud-vocabulary.yml](vocabulary/salesforce-sales-cloud-vocabulary.yml) | Salesforce Sales Cloud domain vocabulary |

## Maintainers

- Kin Lane (kin@apievangelist.com)
