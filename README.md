# Webflow (webflow)
Webflow is a visual web development platform that lets teams design, build, and launch websites without writing code. Their developer platform offers a comprehensive REST Data API and Designer Extension API, enabling developers to programmatically manage sites, CMS content, ecommerce, assets, and build custom extensions for the Webflow Designer.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - CMS, Web Development, No-Code, Ecommerce

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-03

## APIs

### Webflow Data API
The Webflow Data API is a RESTful API that provides access to Webflow sites, pages, CMS collections, ecommerce products and orders, assets, users, and forms. All V2 API endpoints start with https://api.webflow.com/v2 and use OAuth 2.0 for authentication.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - CMS, Ecommerce, Sites, Content Management

#### Properties

- [Documentation](https://developers.webflow.com/data/reference/rest-introduction)
- [Getting Started](https://developers.webflow.com/data/reference/rest-introduction/quick-start)
- [Authentication](https://developers.webflow.com/data/reference/authentication)
- [Rate Limits](https://developers.webflow.com/data/reference/rate-limits)
- [Change Log](https://developers.webflow.com/data/v2.0.0/changelog)
- [SDKs](https://developers.webflow.com/data/reference/sdks)
- [OpenAPI](openapi/webflow-data-api-openapi.yml)
- [AsyncAPI](asyncapi/webflow-webhooks-asyncapi.yml)

### Webflow Designer Extension API
The Webflow Designer Extension API allows developers to build extensions that run inside the Webflow Designer, enabling custom UI panels and interactions with the designer canvas and site content.

**Human URL:** [https://developers.webflow.com/designer/reference/introduction](https://developers.webflow.com/designer/reference/introduction)

#### Tags:

 - Designer, Extensions, Plugins

#### Properties

- [Documentation](https://developers.webflow.com/designer/reference/introduction)
- [Getting Started](https://developers.webflow.com/designer/docs/getting-started-designer-extensions)

### Webflow Meta API
The Webflow Meta API provides endpoints for retrieving information about the authorized user and introspecting API tokens, including scopes and permissions.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Authentication, Tokens, Meta

#### Properties

- [OpenAPI](openapi/webflow-meta-openapi.yml)

### Webflow Sites API
The Webflow Sites API provides endpoints for managing Webflow sites within a workspace, including creating, updating, publishing, and deleting sites, as well as managing custom domains, redirects, robots.txt, and site activity logs.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Sites, Domains, Publishing

#### Properties

- [OpenAPI](openapi/webflow-sites-openapi.yml)

### Webflow Pages API
The Webflow Pages API provides endpoints for listing, retrieving, and updating page metadata and DOM content for pages within a Webflow site.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Pages, Content, DOM

#### Properties

- [OpenAPI](openapi/webflow-pages-openapi.yml)

### Webflow Collections API
The Webflow Collections API provides endpoints for managing CMS collections, including creating, listing, and deleting collections, as well as managing collection fields and their configurations.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - CMS, Collections, Fields

#### Properties

- [OpenAPI](openapi/webflow-collections-openapi.yml)

### Webflow CMS Items API
The Webflow CMS Items API provides endpoints for creating, reading, updating, deleting, and publishing collection items, including support for bulk operations and live/staged item management.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - CMS, Items, Content Management

#### Properties

- [OpenAPI](openapi/webflow-items-openapi.yml)

### Webflow Components API
The Webflow Components API provides endpoints for listing components within a site, and retrieving or updating component content and properties.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Components, Design, Reusable

#### Properties

- [OpenAPI](openapi/webflow-components-openapi.yml)

### Webflow Assets API
The Webflow Assets API provides endpoints for uploading, listing, updating, and deleting assets and asset folders within a Webflow site.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Assets, Files, Media

#### Properties

- [OpenAPI](openapi/webflow-assets-openapi.yml)

### Webflow Forms API
The Webflow Forms API provides endpoints for listing forms, retrieving form schemas, and managing form submissions including listing, modifying, and deleting submissions.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Forms, Submissions

#### Properties

- [OpenAPI](openapi/webflow-forms-openapi.yml)

### Webflow Products and SKUs API
The Webflow Products and SKUs API provides endpoints for managing ecommerce products and their SKU variants, including creating, listing, updating products and creating or updating SKUs.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Ecommerce, Products, SKUs

#### Properties

- [OpenAPI](openapi/webflow-products-openapi.yml)

### Webflow Orders API
The Webflow Orders API provides endpoints for listing, retrieving, and updating ecommerce orders, as well as fulfilling, unfulfilling, and refunding orders.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Ecommerce, Orders, Fulfillment

#### Properties

- [OpenAPI](openapi/webflow-orders-openapi.yml)

### Webflow Inventory API
The Webflow Inventory API provides endpoints for listing and updating inventory quantities for ecommerce product SKUs.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Ecommerce, Inventory, Stock

#### Properties

- [OpenAPI](openapi/webflow-inventory-openapi.yml)

### Webflow Ecommerce Settings API
The Webflow Ecommerce Settings API provides an endpoint for retrieving the ecommerce configuration settings for a Webflow site.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Ecommerce, Settings, Configuration

#### Properties

- [OpenAPI](openapi/webflow-ecommerce-settings-openapi.yml)

### Webflow Webhooks API
The Webflow Webhooks API provides endpoints for registering, listing, retrieving, and removing webhooks that deliver real-time event notifications for a Webflow site.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Webhooks, Events, Notifications

#### Properties

- [OpenAPI](openapi/webflow-webhooks-openapi.yml)

### Webflow Custom Code API
The Webflow Custom Code API provides endpoints for adding, updating, and deleting custom JavaScript code on sites and pages, as well as registering and managing hosted or inline scripts.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Custom Code, JavaScript, Scripts

#### Properties

- [OpenAPI](openapi/webflow-custom-code-openapi.yml)

### Webflow Comments API
The Webflow Comments API provides endpoints for listing comment threads and retrieving comment replies within a Webflow site.

**Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags:

 - Comments, Collaboration

#### Properties

- [OpenAPI](openapi/webflow-comments-openapi.yml)

## Common Properties

- [Portal](https://developers.webflow.com/)
- [Documentation](https://developers.webflow.com/data/docs/data-clients)
- [Getting Started](https://developers.webflow.com/data/reference/rest-introduction/quick-start)
- [Website](https://webflow.com/)
- [Blog](https://webflow.com/blog)
- [Support](https://help.webflow.com/)
- [Community](https://forum.webflow.com/)
- [LearningCenter](https://university.webflow.com/)
- [GitHubOrganization](https://github.com/webflow)
- [TermsOfService](https://webflow.com/legal/terms)
- [PrivacyPolicy](https://webflow.com/legal/privacy)
- [Status](https://status.webflow.com/)
- [Login](https://webflow.com/login)
- [Sign Up](https://webflow.com/signup)
- [Marketplace](https://webflow.com/marketplace)
- [Authentication](https://developers.webflow.com/data/reference/authentication)
- [Rate Limits](https://developers.webflow.com/data/reference/rate-limits)
- [Change Log](https://developers.webflow.com/data/v2.0.0/changelog)
- [SDKs](https://developers.webflow.com/data/reference/sdks)
- [Webhooks](https://developers.webflow.com/data/docs/working-with-webhooks)

## Features

| Name | Description |
|------|-------------|
| Visual Web Builder | Drag-and-drop visual design with clean, production-ready HTML/CSS/JS output. |
| CMS API | Programmatic management of CMS collections and items for dynamic content publishing. |
| Ecommerce API | Complete ecommerce API for products, SKUs, orders, inventory, and payment integration. |
| OAuth 2.0 | Secure OAuth 2.0 authorization for building Webflow App integrations. |
| Webhooks | Real-time event notifications for form submissions, publishing, ecommerce events, and CMS changes. |
| AsyncAPI Webhooks | AsyncAPI specification documenting all Webflow webhook event schemas. |
| Designer Extensions | Build custom panels and tools that run inside the Webflow Designer application. |
| Site Publishing API | Programmatically publish Webflow sites to staging or custom production domains. |

## Use Cases

| Name | Description |
|------|-------------|
| Headless CMS | Use Webflow as a headless CMS, managing content via the API with any frontend framework. |
| Content Automation | Automatically create, update, and publish CMS items from external databases or APIs. |
| Ecommerce Integration | Sync Webflow product catalog and orders with ERP, PIM, or inventory management systems. |
| Multi-Site Management | Manage content and publishing across multiple Webflow sites from a centralized platform. |
| Form Processing | Process form submissions via webhooks to integrate with CRM or marketing automation. |
| Site Deployment Pipeline | Trigger Webflow site publishing as part of automated content approval or CI/CD workflows. |

## Integrations

| Name | Description |
|------|-------------|
| Zapier | No-code Webflow integration for automating workflows with 5,000+ apps. |
| Make (Integromat) | Visual automation platform for complex Webflow workflow automation. |
| Airtable | Connect Airtable as a data source for Webflow CMS content. |
| HubSpot | Sync Webflow form submissions and data with HubSpot CRM. |
| Shopify | Import Shopify product catalog into Webflow ecommerce. |
| Memberstack | Add membership and authentication features to Webflow sites. |

## Artifacts

Machine-readable API specifications and schemas organized by format.

### OpenAPI

- [Webflow Data API](openapi/webflow-data-api-openapi.yml)
- [Webflow Meta API](openapi/webflow-meta-openapi.yml)
- [Webflow Sites API](openapi/webflow-sites-openapi.yml)
- [Webflow Pages API](openapi/webflow-pages-openapi.yml)
- [Webflow Collections API](openapi/webflow-collections-openapi.yml)
- [Webflow CMS Items API](openapi/webflow-items-openapi.yml)
- [Webflow Components API](openapi/webflow-components-openapi.yml)
- [Webflow Assets API](openapi/webflow-assets-openapi.yml)
- [Webflow Forms API](openapi/webflow-forms-openapi.yml)
- [Webflow Products and SKUs API](openapi/webflow-products-openapi.yml)
- [Webflow Orders API](openapi/webflow-orders-openapi.yml)
- [Webflow Inventory API](openapi/webflow-inventory-openapi.yml)
- [Webflow Ecommerce Settings API](openapi/webflow-ecommerce-settings-openapi.yml)
- [Webflow Webhooks API](openapi/webflow-webhooks-openapi.yml)
- [Webflow Custom Code API](openapi/webflow-custom-code-openapi.yml)
- [Webflow Comments API](openapi/webflow-comments-openapi.yml)

### AsyncAPI

- [Webflow Webhooks Events](asyncapi/webflow-webhooks-asyncapi.yml)

### JSON Schema

- [Webflow Site](json-schema/webflow-site-schema.json)
- [Webflow Collection Item](json-schema/webflow-collection-item-schema.json)
- [Webflow Order](json-schema/webflow-order-schema.json)
- [Webflow Webhook](json-schema/webflow-webhook-schema.json)

### JSON Structure

- [Webflow Site](json-structure/webflow-site-structure.json)
- [Webflow Collection Item](json-structure/webflow-collection-item-structure.json)
- [Webflow Order](json-structure/webflow-order-structure.json)
- [Webflow Webhook](json-structure/webflow-webhook-structure.json)

### JSON-LD

- [Webflow Context](json-ld/webflow-context.jsonld)

### Examples

- [Webflow Site](examples/webflow-site-example.json)
- [Webflow Collection Item](examples/webflow-collection-item-example.json)
- [Webflow Order](examples/webflow-order-example.json)
- [Webflow Webhook](examples/webflow-webhook-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Webflow Data API](capabilities/shared/data-api.yaml) — 12 operations for sites, collections, items, and webhooks

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [CMS and Ecommerce](capabilities/cms-and-ecommerce.yaml) | Data API | 10 | Content Manager, Developer, Ecommerce Manager |

## Vocabulary

- [Webflow Vocabulary](vocabulary/webflow-vocabulary.yml) — Unified taxonomy mapping 10 APIs, 13 resources, 9 actions, 1 workflow, and 5 personas

## Rules

- [Webflow Spectral Rules](rules/webflow-spectral-rules.yml) — 26 rules across 13 categories enforcing Webflow API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
