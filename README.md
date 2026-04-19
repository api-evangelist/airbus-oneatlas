# Airbus OneAtlas

Airbus OneAtlas is the commercial geospatial platform from Airbus Defence and Space, providing
developer APIs for accessing high-resolution satellite imagery, elevation data, basemaps, and
radar data. The platform covers optical imagery via the Living Library and Pay-Per-Order services,
satellite tasking for new acquisitions, WorldDEM global elevation data, SAR radar imagery, and
seamless basemap tiles.

- **Developer Portal**: https://api.oneatlas.airbus.com/

## APIs

- **OneAtlas Data Living Library** — Stream continuously updated satellite imagery with search and filtering
  - OpenAPI: [openapi/oneatlas-data-living-library-openapi.yml](openapi/oneatlas-data-living-library-openapi.yml)

- **OneAtlas Data Pay-Per-Order API** — Purchase archived satellite imagery on demand
  - OpenAPI: [openapi/oneatlas-data-pay-per-order-api-openapi.yml](openapi/oneatlas-data-pay-per-order-api-openapi.yml)

- **OneAtlas Data Pay-Per-Order Tasking API** — Commission new satellite acquisitions of specific areas
  - OpenAPI: [openapi/oneatlas-data-pay-per-order-tasking-api-openapi.yml](openapi/oneatlas-data-pay-per-order-tasking-api-openapi.yml)

- **OneAtlas Basemap API** — Access seamless satellite-derived basemap tiles
  - OpenAPI: [openapi/oneatlas-basemap-api-openapi.yml](openapi/oneatlas-basemap-api-openapi.yml)

- **OneAtlas Radar API** — Search and task SAR radar satellite imagery
  - OpenAPI: [openapi/oneatlas-radar-api-openapi.yml](openapi/oneatlas-radar-api-openapi.yml)

- **OneAtlas WorldDEM API** — Retrieve global digital elevation model data at up to 12m resolution
  - OpenAPI: [openapi/oneatlas-worlddem-api-openapi.yml](openapi/oneatlas-worlddem-api-openapi.yml)

## Resources

- [Developer Portal](https://api.oneatlas.airbus.com/)
- [Getting Started](https://api.oneatlas.airbus.com/getting-started/)
- [Authentication Guide](https://api.oneatlas.airbus.com/getting-started/authentication/)
- [Release Notes](https://api.oneatlas.airbus.com/releases/)
- [Status](https://status.oneatlas.airbus.com/)
- [Airbus GitHub](https://github.com/airbusgeo)

## Data Models

This repository includes 80 JSON Schema definitions extracted from the OpenAPI specifications,
covering catalog items, activities, tasking orders, API keys, geometry types, and more.

- [json-schema/](json-schema/) — JSON Schema (draft/2020-12) definitions
- [json-structure/](json-structure/) — JSON Structure (json-structure.org) definitions
- [examples/](examples/) — Example instances of all data models
- [json-ld/oneatlas-context.jsonld](json-ld/oneatlas-context.jsonld) — JSON-LD 1.1 context with schema.org and GeoSPARQL mappings

## Rules and Governance

- [rules/oneatlas-spectral-rules.yml](rules/oneatlas-spectral-rules.yml) — Spectral ruleset for API convention enforcement

## Capabilities

- [capabilities/shared/oneatlas-api.yaml](capabilities/shared/oneatlas-api.yaml) — Naftiko shared capability definition
- [capabilities/oneatlas-geospatial-data-access.yaml](capabilities/oneatlas-geospatial-data-access.yaml) — Workflow capability with 5 MCP tools

## Vocabulary

- [vocabulary/oneatlas-vocabulary.yaml](vocabulary/oneatlas-vocabulary.yaml) — 6 resources, 7 actions
