# Folk (folk-app)

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
