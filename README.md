# Enode (enode)

Enode provides a single API to connect and control electric vehicles, chargers, HVAC systems, batteries, solar inverters, and smart meters across more than a thousand hardware brands. The energy-transition API links end-user devices via OAuth, normalizes telemetry, and exposes smart-charging and device-control endpoints for energy apps, VPPs, and home energy management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/enode/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/enode/refs/heads/main/apis.yml)

## Tags

- Energy
- Electric Vehicles
- EV Charging
- Smart Charging
- Energy Transition

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Enode Users & Link API

Create and manage end users and generate Link sessions so users can authorize Enode to access their connected energy devices via vendor OAuth.

- **Human URL:** [https://developers.enode.com/api/reference#users](https://developers.enode.com/api/reference#users)
- **Base URL:** `https://enode-api.production.enode.io`

#### Tags

- Users
- Link
- OAuth

#### Properties

- [Documentation](https://developers.enode.com/docs/linking)
- [API Reference](https://developers.enode.com/api/reference#users)
- [OpenAPI](openapi/enode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/enode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enode Vehicles API

List and read connected electric vehicles, retrieve charge state, battery, location, and odometer telemetry, and issue charge start/stop and max-current control actions.

- **Human URL:** [https://developers.enode.com/api/reference#vehicles](https://developers.enode.com/api/reference#vehicles)
- **Base URL:** `https://enode-api.production.enode.io`

#### Tags

- Vehicles
- Electric Vehicles
- Telemetry

#### Properties

- [Documentation](https://developers.enode.com/docs/vehicles)
- [API Reference](https://developers.enode.com/api/reference#vehicles)
- [OpenAPI](openapi/enode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/enode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enode Chargers API

List and read connected EV chargers, monitor charge state and power draw, and control charging including start/stop, max-current, and charge-rate limits.

- **Human URL:** [https://developers.enode.com/api/reference#chargers](https://developers.enode.com/api/reference#chargers)
- **Base URL:** `https://enode-api.production.enode.io`

#### Tags

- Chargers
- EV Charging
- Control

#### Properties

- [Documentation](https://developers.enode.com/docs/chargers)
- [API Reference](https://developers.enode.com/api/reference#chargers)
- [OpenAPI](openapi/enode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/enode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enode HVAC API

List and read connected HVAC units such as heat pumps and thermostats, and control set point, mode, schedule following, and permanent hold.

- **Human URL:** [https://developers.enode.com/api/reference#hvacs](https://developers.enode.com/api/reference#hvacs)
- **Base URL:** `https://enode-api.production.enode.io`

#### Tags

- HVAC
- Heat Pumps
- Thermostats

#### Properties

- [Documentation](https://developers.enode.com/docs/hvac)
- [API Reference](https://developers.enode.com/api/reference#hvacs)
- [OpenAPI](openapi/enode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/enode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enode Batteries & Inverters API

List and read connected home batteries and solar inverters, retrieve charge level and production statistics, and set battery operation mode.

- **Human URL:** [https://developers.enode.com/api/reference#batteries](https://developers.enode.com/api/reference#batteries)
- **Base URL:** `https://enode-api.production.enode.io`

#### Tags

- Batteries
- Inverters
- Solar

#### Properties

- [Documentation](https://developers.enode.com/docs/batteries)
- [API Reference](https://developers.enode.com/api/reference#batteries)
- [OpenAPI](openapi/enode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/enode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enode Smart Charging API

Configure smart-charging policies, plans, overrides, and status for vehicles, optimizing charging against electricity tariffs, location, and user deadlines.

- **Human URL:** [https://developers.enode.com/api/reference#smart-charging](https://developers.enode.com/api/reference#smart-charging)
- **Base URL:** `https://enode-api.production.enode.io`

#### Tags

- Smart Charging
- Optimization
- Tariffs

#### Properties

- [Documentation](https://developers.enode.com/docs/smart-charging)
- [API Reference](https://developers.enode.com/api/reference#smart-charging)
- [OpenAPI](openapi/enode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/enode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enode Webhooks API

Register, list, update, test, and delete webhooks to receive near-real-time device-update and user-event notifications instead of polling.

- **Human URL:** [https://developers.enode.com/api/reference#webhooks](https://developers.enode.com/api/reference#webhooks)
- **Base URL:** `https://enode-api.production.enode.io`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developers.enode.com/docs/webhooks)
- [API Reference](https://developers.enode.com/api/reference#webhooks)
- [OpenAPI](openapi/enode-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/enode.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enode.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/enode)
- [LinkedIn](https://www.linkedin.com/company/enode-energy)
- [Website](https://www.enode.com)
- [Documentation](https://developers.enode.com/docs)
- [Plans](plans/enode-plans-pricing.yml)
- [Rate Limits](rate-limits/enode-rate-limits.yml)
- [Fin Ops](finops/enode-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
