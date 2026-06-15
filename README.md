# Red Hat Enterprise Linux (rhel)

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
