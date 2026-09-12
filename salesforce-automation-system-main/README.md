# Salesforce Automation System (salesforce-automation-system)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Salesforce Automation System refers to the collection of APIs and tools within Salesforce for automating business processes, including Flow Builder, approval processes, Process Builder, and Workflow Rules. These capabilities enable organizations to automate CRM, sales, marketing, and customer service workflows programmatically via the Salesforce REST API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Approval Process
- Automation
- CRM
- Flow
- Process Builder
- Salesforce
- Workflow

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Salesforce Flow Automation API

REST API for querying Salesforce Flow definitions via the Tooling API, invoking autolaunched flows as REST actions, and managing approval process submissions and decisions.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v59.0`

#### Tags

- Approval Process
- Automation
- CRM
- Flow
- Salesforce
- Workflow

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm)
- [OpenAPI](openapi/salesforce-automation-flow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-automation-flow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-automation-flow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/salesforce-flow-definition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/salesforce-approval-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/salesforce-automation-system-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/salesforce-automation-system-rules.yml)
- [Capabilities](capabilities/process-automation.yaml)
- [Vocabulary](vocabulary/salesforce-automation-system-vocabulary.yml)

### Salesforce Flow Builder

Visual automation tool for building screen flows, autolaunched flows, record-triggered flows, and scheduled flows without code.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/flow_intro.htm](https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/flow_intro.htm)

#### Tags

- Automation
- Flow
- No-Code
- Salesforce

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/flow_intro.htm)
- [Getting Started](https://trailhead.salesforce.com/content/learn/trails/automate_business_processes)
- [Postman Collection](collections/salesforce-automation-flow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-automation-flow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Approval Processes

Multi-step approval automation for routing records through review chains with configurable criteria, approvers, and post-approval actions.

- **Human URL:** [https://help.salesforce.com/s/articleView?id=sf.approvals_landing_page.htm](https://help.salesforce.com/s/articleView?id=sf.approvals_landing_page.htm)

#### Tags

- Approval
- Automation
- CRM
- Salesforce

#### Properties

- [Documentation](https://help.salesforce.com/s/articleView?id=sf.approvals_landing_page.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_process_approvals.htm)
- [Postman Collection](collections/salesforce-automation-flow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-automation-flow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Developer  Portal](https://developer.salesforce.com/)
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)
- [Trailhead](https://trailhead.salesforce.com/content/learn/trails/automate_business_processes)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm)
- [Blog](https://developer.salesforce.com/blogs)
- [Status Page](https://status.salesforce.com/)
- [Support](https://help.salesforce.com/)
- [Terms of Service](https://www.salesforce.com/company/legal/agreements/)
- [Privacy Policy](https://www.salesforce.com/company/privacy/)
- [GitHub Organization](https://github.com/salesforce)
- [Community](https://trailhead.salesforce.com/trailblazer-community/topics/salesforcedeveloper)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
