# Webflow GraphQL Schema

## Overview

Webflow does not currently offer a public GraphQL API. The platform exposes its functionality exclusively through a RESTful Data API (v2) accessible at `https://api.webflow.com/v2`, with OAuth 2.0 and API key authentication. There is no official GraphQL endpoint from Webflow as of June 2026.

This schema (`webflow-schema.graphql`) is a conceptual GraphQL representation of the Webflow data model, derived from the official Webflow Data API OpenAPI specification and all published REST endpoints. It is intended to support tooling, documentation generation, data modeling, and integration design — not to imply a live GraphQL endpoint exists.

## REST API Reference

- Documentation: https://developers.webflow.com/data/reference/rest-introduction
- Base URL: https://api.webflow.com/v2
- Authentication: OAuth 2.0 (`Authorization: Bearer <token>`) or API Key (`Authorization: Bearer <api_key>`)

## Data Model Coverage

The conceptual schema covers all major Webflow resource domains:

- **Meta / Auth** — authorized user, token introspection, workspaces, audit logs
- **Sites** — site management, custom domains, publishing, redirects, robots.txt, activity logs, plan info
- **Pages** — page metadata and DOM content
- **Components** — reusable designer components and their content
- **Collections** — CMS collection definitions and field configurations
- **Items** — CMS collection items (live and staged), bulk operations
- **Assets** — file assets and asset folders
- **Forms** — form schemas and form submissions
- **Ecommerce** — products, SKUs, orders, inventory, ecommerce settings
- **Custom Code** — inline and hosted scripts for sites and pages
- **Webhooks** — webhook registrations and event types
- **Comments** — comment threads and replies

## Webhook Event Types

The following webhook event types are defined in the Webflow AsyncAPI spec:

- `form_submission`
- `site_publish`
- `ecomm_new_order`
- `ecomm_order_changed`
- `ecomm_inventory_changed`
- `collection_item_created`
- `collection_item_changed`
- `collection_item_deleted`
- `collection_item_published`
- `collection_item_unpublished`
- `page_created`
- `page_metadata_updated`
- `page_deleted`
- `comment_created`

## Schema File

See `webflow-schema.graphql` for the full conceptual GraphQL SDL covering 55+ types derived from the Webflow REST API.

## Notes

- This is a **conceptual schema only** — there is no live GraphQL endpoint to query.
- All field names and types are modeled after Webflow's published REST API request/response shapes.
- If Webflow launches a GraphQL API in the future, this schema should be validated against the real introspection result and updated accordingly.
- GitHub: https://github.com/webflow
- Developer Portal: https://developers.webflow.com/
