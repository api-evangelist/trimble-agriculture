# Trimble Agriculture

The Trimble Agriculture Cloud is an independent, brand-agnostic platform that connects infield devices and operational workflows to more efficiently execute crop production plans and collect robust agricultural datasets. The API (now operating as PTxAg FarmENGAGE) provides REST endpoints for farm setup, field management, crop zones, equipment activities, work orders, prescriptions, materials, and imagery. The platform serves over 180 million customer acres globally.

**URL:** [View APIs.yml](https://raw.githubusercontent.com/api-evangelist/trimble-agriculture/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-03

## APIs

### Trimble Agriculture Data API

REST API for managing precision agriculture data including farms, fields, crop zones, equipment activities, work orders, prescriptions, materials, and imagery.

**Human URL:** [https://agdeveloper.trimble.com/api-docs](https://agdeveloper.trimble.com/api-docs)

#### Tags

- Agriculture, Farming, Field Management, Prescriptions, Equipment Activities, Work Orders, Crop Zones, Boundaries

#### Properties

- [Documentation](https://agdeveloper.trimble.com/api-docs)
- [Getting Started](https://agdeveloper.trimble.com/)
- [OpenAPI](openapi/trimble-agriculture-openapi.yml)

### Trimble Agriculture Telematics API

Provides access to real-time and historical equipment telematics from connected Trimble displays.

**Human URL:** [https://agdeveloper.trimble.com/api-docs](https://agdeveloper.trimble.com/api-docs)

## OpenAPI Specifications

| Specification | Description |
|---|---|
| [Trimble Agriculture API](openapi/trimble-agriculture-openapi.yml) | Full Agriculture Data API covering farms, fields, crop zones, equipment activities, work orders, prescriptions, materials, boundaries, and imagery |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [Trimble Agriculture Rules](rules/trimble-agriculture-rules.yml) | Spectral ruleset enforcing Trimble Agriculture API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/trimble-agriculture.yaml](capabilities/shared/trimble-agriculture.yaml) | Per-API consumed definition for Trimble Agriculture Data API |

### Workflow Capabilities

| Capability | Description |
|---|---|
| [capabilities/precision-farming.yaml](capabilities/precision-farming.yaml) | Precision farming workflow: farms, fields, crop zones, equipment activities, work orders, prescriptions (10 tools) |

## JSON Schema

| Schema | Description |
|---|---|
| [json-schema/trimble-agriculture-cropzone-schema.json](json-schema/trimble-agriculture-cropzone-schema.json) | JSON Schema for crop zone entities |
| [json-schema/trimble-agriculture-activity-schema.json](json-schema/trimble-agriculture-activity-schema.json) | JSON Schema for equipment activity entities |

## JSON Structure

| Structure | Description |
|---|---|
| [json-structure/trimble-agriculture-cropzone-structure.json](json-structure/trimble-agriculture-cropzone-structure.json) | Structure documentation for crop zones |

## JSON-LD Context

| Context | Description |
|---|---|
| [json-ld/trimble-agriculture-context.jsonld](json-ld/trimble-agriculture-context.jsonld) | JSON-LD context mapping Trimble Agriculture vocabulary to schema.org and GeoSPARQL |

## Examples

| Example | Description |
|---|---|
| [examples/trimble-agriculture-list-farms-example.json](examples/trimble-agriculture-list-farms-example.json) | List farms for an organization |
| [examples/trimble-agriculture-list-equipment-activities-example.json](examples/trimble-agriculture-list-equipment-activities-example.json) | List planting activities |
| [examples/trimble-agriculture-create-work-order-example.json](examples/trimble-agriculture-create-work-order-example.json) | Create a herbicide application work order |

## Vocabulary

| File | Description |
|---|---|
| [vocabulary/trimble-agriculture-vocabulary.yml](vocabulary/trimble-agriculture-vocabulary.yml) | Domain vocabulary for precision agriculture concepts |

## Common Links

- **Website:** [https://agriculture.trimble.com/](https://agriculture.trimble.com/)
- **Developer Portal:** [https://agdeveloper.trimble.com/](https://agdeveloper.trimble.com/)
- **Documentation:** [https://agdeveloper.trimble.com/api-docs](https://agdeveloper.trimble.com/api-docs)
- **Sign Up:** [https://agdeveloper.trimble.com/](https://agdeveloper.trimble.com/)
- **Contact:** ag_api@trimble.com

## Maintainers

- **Kin Lane** - kin@apievangelist.com
