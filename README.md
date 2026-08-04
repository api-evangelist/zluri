# Zluri (zluri)

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

Zluri is a SaaS management and operations platform that helps organizations discover, govern, and optimize all their cloud applications. By connecting to SSO, finance, HR systems, and app APIs, it builds a unified system of record for SaaS usage, users, licenses, and spend. IT, finance, and procurement teams use Zluri to surface shadow IT, eliminate redundant or underused tools, rightsize licenses, and manage renewals and vendor relationships.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zluri/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zluri/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Access Management
- SaaS Management

## Timestamps

- **Created:** 2025-07-15
- **Modified:** 2026-05-19

## APIs

### Zluri

The Zluri external API enables organizations to push data from custom and on-premise applications into Zluri when no native connector is available. The API supports syncing users, applications, contracts, transactions, groups, roles, and activities. It follows a sync-based workflow where you create a sync session, upload data in paginated batches, and finish the sync to make data visible in Zluri.

- **Human URL:** [https://www.zluri.com/](https://www.zluri.com/)

#### Tags

- Access Management
- FinOps
- SaaS Management

#### Properties

- [Documentation](https://www.zluri.com/)
- [Documentation](https://api-docs.zluri.dev/)
- [Portal](https://developers.zluri.com/)
- [OpenAPI](openapi/zluri-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zluri-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zluri-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/instance.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sync.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/snapshot-data-upload.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/fact-data-upload.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/webhook.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/error.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/instance-structure.json)
- [JSON Structure](json-structure/sync-structure.json)
- [JSON Structure](json-structure/snapshot-data-upload-structure.json)
- [JSON Structure](json-structure/fact-data-upload-structure.json)
- [JSON Structure](json-structure/webhook-structure.json)
- [JSON Structure](json-structure/error-structure.json)
- [Example](examples/zluri-list-instances-example.json)
- [Example](examples/zluri-create-sync-example.json)
- [Example](examples/zluri-upload-snapshot-data-example.json)
- [Example](examples/zluri-upload-fact-data-example.json)
- [Example](examples/zluri-create-webhook-example.json)

## Common Properties

- [GitHub Organization](https://github.com/ZluriHQ)
- [LinkedIn](https://www.linkedin.com/company/zluri)
- [Customers](https://www.zluri.com/case-studies)
- [Security](https://www.zluri.com/security)
- [Events](https://www.zluri.com/events)
- [Contact](https://www.zluri.com/contact-us)
- [Blog](https://www.zluri.com/blog?all=All)
- [White Papers](https://www.zluri.com/whitepapers)
- [Webinars](https://www.zluri.com/webinars)
- [Login](https://support.zluri.com/support/login)
- [Trust Center](https://trust.zluri.com/)
- [Terms of Service](https://www.zluri.com/policy/terms-and-conditions)
- [Privacy Policy](https://www.zluri.com/policy/privacy-policy)
- [JSON-LD](json-ld/zluri-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/zluri-spectral.yaml)
- [Vocabulary](vocabulary/zluri-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](https://www.zluri.com/integrations)
- [L L Ms Txt](https://developers.zluri.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
