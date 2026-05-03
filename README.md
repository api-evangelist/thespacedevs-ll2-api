# TheSpaceDevs LL2 API

TheSpaceDevs Launch Library 2 is the official successor to the Launch Library API. It provides comprehensive data on rocket launches, space events, crewed spaceflight, astronauts, spacecraft, space stations, and celestial bodies. The API delivers real-time updates on launch schedules, mission timelines, and historical data on all global space missions.

**URL:** [https://raw.githubusercontent.com/api-evangelist/thespacedevs-ll2-api/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/thespacedevs-ll2-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Space
- Satellites
- Launches
- Rockets
- Astronauts

## Timestamps

- **Created:** 2024-11-07
- **Modified:** 2026-05-03

## APIs

### TheSpaceDevs Launch Library 2 API

Rocket launches, space events, and crewed spaceflight. The Launch Library 2 API provides comprehensive data on all aspects of global spaceflight.

**Human URL:** [https://thespacedevs.com/llapi](https://thespacedevs.com/llapi)

**Base URL:** https://ll.thespacedevs.com

#### Tags

- Space
- Launches
- Rockets
- Astronauts
- Satellites
- Spacecraft
- Space Stations

#### Key Operations

| Method | Path | Summary |
|--------|------|---------|
| GET | /2.3.0/launches/upcoming/ | List Upcoming Launches |
| GET | /2.3.0/launches/previous/ | List Previous Launches |
| GET | /2.3.0/launches/{id}/ | Get Launch |
| GET | /2.3.0/events/upcoming/ | List Upcoming Events |
| GET | /2.3.0/astronauts/ | List Astronauts |
| GET | /2.3.0/astronauts/{id}/ | Get Astronaut |
| GET | /2.3.0/space_stations/ | List Space Stations |
| GET | /2.3.0/spacecraft/ | List Spacecraft |
| GET | /2.3.0/agencies/ | List Agencies |
| GET | /2.3.0/pads/ | List Launch Pads |
| GET | /2.3.0/locations/ | List Locations |
| GET | /2.3.0/spacewalks/ | List Spacewalks |
| GET | /2.3.0/expeditions/ | List Expeditions |
| GET | /2.3.0/celestial_bodies/ | List Celestial Bodies |

(116 total operations)

#### Properties

- [Documentation](https://thespacedevs.com/llapi)
- [OpenAPI](openapi/thespacedevs-ll2-api-openapi.yml)
- [JSON Schema](json-schema/thespacedevs-launch-schema.json)
- [JSON-LD](json-ld/thespacedevs-context.jsonld)
- [JSON Structure](json-structure/thespacedevs-structure.json)
- [Spectral Rules](rules/thespacedevs-rules.yml)
- [Capabilities](capabilities/launch-tracking.yaml)
- [Vocabulary](vocabulary/thespacedevs-vocabulary.yml)

## Artifacts

### OpenAPI Specs

- [TheSpaceDevs LL2 API](openapi/thespacedevs-ll2-api-openapi.yml)

### JSON Schemas

- [Space Launch Record](json-schema/thespacedevs-launch-schema.json)

### JSON Structure

- [TheSpaceDevs Structure](json-structure/thespacedevs-structure.json)

### JSON-LD

- [TheSpaceDevs Context](json-ld/thespacedevs-context.jsonld)

### Examples

- [List Upcoming Launches](examples/thespacedevs-list-upcoming-launches-example.json)
- [List Astronauts](examples/thespacedevs-list-astronauts-example.json)

### Spectral Rules

- [TheSpaceDevs Rules](rules/thespacedevs-rules.yml)

### Capabilities

- [Space Mission Tracking](capabilities/launch-tracking.yaml)

**Shared Definitions:**

- [Launch Library 2 API](capabilities/shared/ll2-api.yaml)

### Vocabulary

- [TheSpaceDevs Vocabulary](vocabulary/thespacedevs-vocabulary.yml)

## Common Properties

- [Website](https://thespacedevs.com/)
- [API Documentation](https://ll.thespacedevs.com/docs/)
- [GitHub Organization](https://github.com/TheSpaceDevs)
- [Discord Community](https://discord.gg/p7ntkNA)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
