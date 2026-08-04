# Red Hat Enterprise Linux (rhel)

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

Red Hat Enterprise Linux (RHEL) is the world's leading enterprise Linux platform, providing APIs and services for subscription management, security insights, compliance monitoring, vulnerability assessment, patch management, content delivery, and automation. The Red Hat Hybrid Cloud Console exposes a comprehensive suite of REST APIs for managing RHEL systems at scale.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Automation
- Compliance
- Enterprise
- Linux
- Operating System
- Red Hat
- RHEL
- Security
- Subscription Management
- Vulnerability Management

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Red Hat Subscription Management API

API for managing RHEL subscriptions, entitlements, and system registrations. Enables automation of subscription lifecycle, system registration, and entitlement queries using OAuth 2.0 authentication.

- **Human URL:** [https://access.redhat.com/management/api](https://access.redhat.com/management/api)
- **Base URL:** `https://api.access.redhat.com/management/v1`

#### Tags

- Entitlements
- Systems Management
- Subscriptions

#### Properties

- [Documentation](https://access.redhat.com/management/api/docs)
- [OpenAPI](https://api.access.redhat.com/management/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/openapi/rhel-subscription-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://access.redhat.com/articles/3626371)
- [Postman Collection](collections/rhel-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rhel-subscription-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-subscription-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat Insights API

Predictive analytics and remediation service for RHEL systems. Provides advisor recommendations based on 20+ years of Red Hat support experience, covering security, performance, availability, and stability issues.

- **Human URL:** [https://console.redhat.com/docs/api/insights](https://console.redhat.com/docs/api/insights)
- **Base URL:** `https://console.redhat.com/api/insights/v1`

#### Tags

- Analytics
- Monitoring
- Remediation

#### Properties

- [Documentation](https://console.redhat.com/docs/api/insights)
- [OpenAPI](https://cloud.redhat.com/api/insights/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rhel-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rhel-subscription-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-subscription-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat Security Data API

API for accessing security advisories, CVE data, bug fixes, and enhancement updates for Red Hat products. Enables automated vulnerability assessment and tracking of RHEL-relevant CVEs with severity filtering.

- **Human URL:** [https://access.redhat.com/documentation/en-us/red_hat_security_data_api/](https://access.redhat.com/documentation/en-us/red_hat_security_data_api/)
- **Base URL:** `https://access.redhat.com/hydra/rest/securitydata`

#### Tags

- Advisories
- CVE
- Errata
- Security
- Vulnerability Management

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_security_data_api/1.0/)
- [Github Repository](https://github.com/RedHatOfficial/rhsecapi)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/openapi/rhel-security-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rhel-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rhel-subscription-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-subscription-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat Insights Compliance API

API for assessing, monitoring, and reporting on security-policy compliance of RHEL systems. Based on the Security Content Automation Protocol (SCAP), enables creation and management of compliance policies and reports.

- **Human URL:** [https://console.redhat.com/docs/api/compliance](https://console.redhat.com/docs/api/compliance)
- **Base URL:** `https://console.redhat.com/api/compliance/v2`

#### Tags

- Compliance
- SCAP
- Security

#### Properties

- [Documentation](https://console.redhat.com/docs/api/compliance)
- [OpenAPI](https://console.redhat.com/api/compliance/v2/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rhel-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rhel-subscription-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-subscription-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat Insights Vulnerability API

API for managing vulnerabilities on RHEL systems. Integrates with the Red Hat CVE database to assess outstanding CVEs and provide remediation guidance for registered RHEL hosts.

- **Human URL:** [https://console.redhat.com/docs/api/vulnerability](https://console.redhat.com/docs/api/vulnerability)
- **Base URL:** `https://console.redhat.com/api/vulnerability/v1`

#### Tags

- CVE
- Remediation
- Security
- Vulnerability Management

#### Properties

- [Documentation](https://console.redhat.com/docs/api/vulnerability)
- [OpenAPI](https://console.redhat.com/api/vulnerability/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rhel-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rhel-subscription-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-subscription-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat Insights Patch API

API for patch management of RHEL systems. Tracks applicable advisories and patches for registered systems, enabling automated patch compliance reporting and remediation workflows.

- **Human URL:** [https://console.redhat.com/docs/api/patch](https://console.redhat.com/docs/api/patch)
- **Base URL:** `https://console.redhat.com/api/patch/v3`

#### Tags

- Advisories
- Patch Management
- Updates

#### Properties

- [Documentation](https://console.redhat.com/docs/api/patch)
- [OpenAPI](https://console.redhat.com/api/patch/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rhel-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rhel-subscription-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-subscription-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat Insights Host Inventory API

API for managing the inventory of RHEL systems registered with Red Hat Insights. Provides host metadata, system profiles, and group management for hybrid cloud environments.

- **Human URL:** [https://console.redhat.com/docs/api/inventory](https://console.redhat.com/docs/api/inventory)
- **Base URL:** `https://console.redhat.com/api/inventory/v1`

#### Tags

- Hosts
- Inventory
- Systems Management

#### Properties

- [Documentation](https://console.redhat.com/docs/api/inventory)
- [OpenAPI](https://console.redhat.com/api/inventory/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rhel-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rhel-subscription-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-subscription-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Red Hat Insights Remediations API

API for creating and executing Ansible-based remediation playbooks for RHEL systems. Integrates with Insights advisor, vulnerability, and compliance services to automate issue resolution at scale.

- **Human URL:** [https://console.redhat.com/docs/api/remediations](https://console.redhat.com/docs/api/remediations)
- **Base URL:** `https://console.redhat.com/api/remediations/v1`

#### Tags

- Ansible
- Automation
- Remediation

#### Properties

- [Documentation](https://console.redhat.com/docs/api/remediations)
- [OpenAPI](https://console.redhat.com/api/remediations/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rhel-security-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-security-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rhel-subscription-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rhel-subscription-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://access.redhat.com)
- [Developer](https://developers.redhat.com/products/rhel)
- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/)
- [Hybrid Cloud Console](https://console.redhat.com)
- [A P I Management](https://access.redhat.com/management/api)
- [Github Org](https://github.com/RedHatOfficial)
- [Github Org](https://github.com/redhat-cop)
- [Support](https://access.redhat.com/support)
- [Terms of Service](https://www.redhat.com/en/about/terms-use)
- [Privacy Policy](https://www.redhat.com/en/about/privacy-policy)
- [Website](https://www.redhat.com)
- [Authentication](https://access.redhat.com/articles/3626371)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/rules/rhel-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/json-schema/rhel-cve-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/json-schema/rhel-system-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/json-ld/rhel-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/vocabulary/rhel-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
