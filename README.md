# Enode (enode)

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
