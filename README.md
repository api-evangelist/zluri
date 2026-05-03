# Zluri (zluri)
Zluri is a SaaS management and operations platform that helps organizations discover, govern, and optimize all their cloud applications. By connecting to SSO, finance, HR systems, and app APIs, it builds a unified system of record for SaaS usage, users, licenses, and spend. IT, finance, and procurement teams use Zluri to surface shadow IT, eliminate redundant or underused tools, rightsize licenses, and manage renewals and vendor relationships.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/zluri/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Access Management, SaaS Management

## Timestamps

- **Created:** 2025-07-15
- **Modified:** 2026-05-03

## APIs

### Zluri
The Zluri external API enables organizations to push data from custom and on-premise applications into Zluri when no native connector is available. The API supports syncing users, applications, contracts, transactions, groups, roles, and activities. It follows a sync-based workflow where you create a sync session, upload data in paginated batches, and finish the sync to make data visible in Zluri.

**Human URL:** [https://www.zluri.com/](https://www.zluri.com/)

#### Tags:

 - Access Management, FinOps, SaaS Management

#### Properties

- [Documentation - Zluri Home](https://www.zluri.com/)
- [Documentation - API Docs](https://api-docs.zluri.dev/)
- [Portal](https://developers.zluri.com/)
- [OpenAPI](openapi/zluri-api-openapi.yml)
- [JSONSchema - Instance](json-schema/instance.json)
- [JSONSchema - Sync](json-schema/sync.json)
- [JSONSchema - Snapshot Data Upload](json-schema/snapshot-data-upload.json)
- [JSONSchema - Fact Data Upload](json-schema/fact-data-upload.json)
- [JSONSchema - Webhook](json-schema/webhook.json)
- [JSONSchema - Error](json-schema/error.json)
- [JSONStructure - Instance](json-structure/instance-structure.json)
- [JSONStructure - Sync](json-structure/sync-structure.json)
- [JSONStructure - Snapshot Data Upload](json-structure/snapshot-data-upload-structure.json)
- [JSONStructure - Fact Data Upload](json-structure/fact-data-upload-structure.json)
- [JSONStructure - Webhook](json-structure/webhook-structure.json)
- [JSONStructure - Error](json-structure/error-structure.json)
- [Example - List Instances](examples/zluri-list-instances-example.json)
- [Example - Create Sync](examples/zluri-create-sync-example.json)
- [Example - Upload Snapshot Data](examples/zluri-upload-snapshot-data-example.json)
- [Example - Upload Fact Data](examples/zluri-upload-fact-data-example.json)
- [Example - Create Webhook](examples/zluri-create-webhook-example.json)

## Common Properties

- [Customers](https://www.zluri.com/case-studies)
- [Security](https://www.zluri.com/security)
- [Events](https://www.zluri.com/events)
- [Contact](https://www.zluri.com/contact-us)
- [Blog](https://www.zluri.com/blog?all=All)
- [WhitePapers](https://www.zluri.com/whitepapers)
- [Webinars](https://www.zluri.com/webinars)
- [Login](https://support.zluri.com/support/login)
- [TrustCenter](https://trust.zluri.com/)
- [TermsOfService](https://www.zluri.com/policy/terms-and-conditions)
- [PrivacyPolicy](https://www.zluri.com/policy/privacy-policy)
- [JSONLD](json-ld/zluri-context.jsonld)
- [SpectralRules](rules/zluri-spectral.yaml)
- [NaftikoCapability](capabilities/saas-data-sync.yaml)
- [Vocabulary](vocabulary/zluri-vocabulary.yaml)

## Features

| Name |
|------|
| SaaS Management |
| Access Management |
| Access Requests |
| Access Reviews |
| SOC 2 |
| ISO 27001 |
| HIPAA |
| SOX ITGC |
| PCI DSS |
| User Activity Patterns |
| Manage Renewals |
| SaaS Discovery |
| Security Policies |
| Optimize Spends |
| Smart Contracts |
| Renewal Management |
| Integrations |
| Provisioning |
| Deprovisioning |
| Time Bound Access Controls |

## Use Cases

| Name |
|------|
| Identity Visibility |
| Application Visibility |
| Uncover Shadow IT |
| Monitor AI Apps |
| Identity Lifecycle Management |
| Access Requests |
| Access Reviews |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Zluri API](openapi/zluri-api-openapi.yml)

### JSON Schema

- [Instance](json-schema/instance.json)
- [Sync](json-schema/sync.json)
- [Snapshot Data Upload](json-schema/snapshot-data-upload.json)
- [Fact Data Upload](json-schema/fact-data-upload.json)
- [Webhook](json-schema/webhook.json)
- [Error](json-schema/error.json)

### JSON Structure

- [Instance](json-structure/instance-structure.json)
- [Sync](json-structure/sync-structure.json)
- [Snapshot Data Upload](json-structure/snapshot-data-upload-structure.json)
- [Fact Data Upload](json-structure/fact-data-upload-structure.json)
- [Webhook](json-structure/webhook-structure.json)
- [Error](json-structure/error-structure.json)

### JSON-LD

- [Zluri Context](json-ld/zluri-context.jsonld)

### Examples

- [List Instances](examples/zluri-list-instances-example.json)
- [Create Sync](examples/zluri-create-sync-example.json)
- [Upload Snapshot Data](examples/zluri-upload-snapshot-data-example.json)
- [Upload Fact Data](examples/zluri-upload-fact-data-example.json)
- [Create Webhook](examples/zluri-create-webhook-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Zluri API](capabilities/shared/zluri-api.yaml) — 13 operations for instance, sync, data upload, and webhook management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [SaaS Data Sync](capabilities/saas-data-sync.yaml) | zluri-api | 8 | IT Operations Engineer |

## Vocabulary

- [Zluri Vocabulary](vocabulary/zluri-vocabulary.yaml) — Unified taxonomy mapping 12 resources, 13 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Zluri Spectral Ruleset](rules/zluri-spectral.yaml) — 7 rules across naming, operation, security, and rate-limit categories enforcing Zluri API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
