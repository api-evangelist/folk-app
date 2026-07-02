# Folk (folk-app)

Folk is a lightweight, relationship-focused CRM for people who build their business on relationships. Folk's public REST API - the Folk External API - is date-versioned (base `https://api.folk.app`, resources under `/v1`) and authenticated with a Bearer API key created in workspace settings. It lets you programmatically manage people, companies, groups, deals and other custom objects, notes, reminders, and interactions, and subscribe to real-time changes through webhooks. API access is a paid-plan (Premium / Enterprise) feature.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/folk-app/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/folk-app/refs/heads/main/apis.yml)

## Tags

- CRM
- Relationships
- Contacts
- Sales
- Pipeline
- Webhooks

## Timestamps

- **Created:** 2026-07-02
- **Modified:** 2026-07-02

## APIs

### Folk People API

Create, retrieve, list, update, delete, and search people (contacts) - the core relationship records in Folk - including emails, phones, URLs, group membership, and custom field values.

- **Human URL:** [https://developer.folk.app/api-reference/people](https://developer.folk.app/api-reference/people)
- **Base URL:** `https://api.folk.app/v1`

#### Tags

- People
- Contacts
- CRM

#### Properties

- [Documentation](https://developer.folk.app/api-reference/introduction)
- [API Reference](https://developer.folk.app/api-reference/people)
- [OpenAPI](openapi/folk-app-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/folk-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/folk-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Folk Companies API

Create, retrieve, list, update, delete, and search companies - organization records that people can be associated with, with their own custom fields and group membership.

- **Human URL:** [https://developer.folk.app/api-reference/companies](https://developer.folk.app/api-reference/companies)
- **Base URL:** `https://api.folk.app/v1`

#### Tags

- Companies
- Organizations
- CRM

#### Properties

- [API Reference](https://developer.folk.app/api-reference/companies)
- [OpenAPI](openapi/folk-app-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/folk-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/folk-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Folk Deals and Custom Objects API

Create, retrieve, list, update, delete, and search deals and other group-scoped custom objects, addressed as `/v1/groups/{groupId}/{objectType}`. Deals are the built-in pipeline object; custom objects are a Premium feature.

- **Human URL:** [https://developer.folk.app/api-reference/deals](https://developer.folk.app/api-reference/deals)
- **Base URL:** `https://api.folk.app/v1`

#### Tags

- Deals
- Custom Objects
- Pipeline

#### Properties

- [API Reference](https://developer.folk.app/api-reference/deals)
- [OpenAPI](openapi/folk-app-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/folk-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/folk-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Folk Groups API

List the groups in a workspace and list the custom fields defined on a group for a given entity type (person, company, or object), so integrations can map values to the right group schema.

- **Human URL:** [https://developer.folk.app/api-reference/groups](https://developer.folk.app/api-reference/groups)
- **Base URL:** `https://api.folk.app/v1`

#### Tags

- Groups
- Custom Fields
- Segments

#### Properties

- [API Reference](https://developer.folk.app/api-reference/groups)
- [OpenAPI](openapi/folk-app-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/folk-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/folk-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Folk Notes API

Create, retrieve, list, update, and delete notes attached to people, companies, or objects to capture free-form context on a relationship.

- **Human URL:** [https://developer.folk.app/api-reference/notes](https://developer.folk.app/api-reference/notes)
- **Base URL:** `https://api.folk.app/v1`

#### Tags

- Notes
- Activity
- CRM

#### Properties

- [API Reference](https://developer.folk.app/api-reference/notes)
- [OpenAPI](openapi/folk-app-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/folk-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/folk-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Folk Reminders API

Create, retrieve, list, update, and delete reminders - dated follow-up tasks tied to contacts - so you never lose track of the next touchpoint.

- **Human URL:** [https://developer.folk.app/api-reference/reminders](https://developer.folk.app/api-reference/reminders)
- **Base URL:** `https://api.folk.app/v1`

#### Tags

- Reminders
- Tasks
- Follow-Up

#### Properties

- [API Reference](https://developer.folk.app/api-reference/reminders)
- [OpenAPI](openapi/folk-app-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/folk-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/folk-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Folk Interactions API

Record an interaction (such as an email, call, or meeting) against a contact to build up the relationship timeline programmatically.

- **Human URL:** [https://developer.folk.app/api-reference/interactions](https://developer.folk.app/api-reference/interactions)
- **Base URL:** `https://api.folk.app/v1`

#### Tags

- Interactions
- Activity
- Timeline

#### Properties

- [API Reference](https://developer.folk.app/api-reference/interactions)
- [OpenAPI](openapi/folk-app-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/folk-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/folk-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Folk Users API

List the users (members) in a workspace, retrieve a user by ID, and get the current authenticated user (`/v1/users/me`) behind the API key.

- **Human URL:** [https://developer.folk.app/api-reference/users](https://developer.folk.app/api-reference/users)
- **Base URL:** `https://api.folk.app/v1`

#### Tags

- Users
- Members
- Workspace

#### Properties

- [API Reference](https://developer.folk.app/api-reference/users)
- [OpenAPI](openapi/folk-app-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/folk-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/folk-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Folk Webhooks API

Create, retrieve, list, update, and delete webhooks that subscribe to real-time change events (person, company, object, note, and reminder created / updated / deleted, plus `reminder.triggered`), with a signing secret for verification. This is Folk's real-time mechanism - there is no WebSocket API.

- **Human URL:** [https://developer.folk.app/api-reference/webhooks](https://developer.folk.app/api-reference/webhooks)
- **Base URL:** `https://api.folk.app/v1`

#### Tags

- Webhooks
- Events
- Real-Time

#### Properties

- [API Reference](https://developer.folk.app/api-reference/webhooks)
- [OpenAPI](openapi/folk-app-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/folk-app.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/folk-app.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/folk-app)
- [Website](https://www.folk.app)
- [Documentation](https://developer.folk.app)
- [Plans](plans/folk-app-plans-pricing.yml)
- [Rate Limits](rate-limits/folk-app-rate-limits.yml)
- [Fin Ops](finops/folk-app-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
