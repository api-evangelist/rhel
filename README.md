# Red Hat Enterprise Linux

Red Hat Enterprise Linux (RHEL) is the world's leading enterprise Linux platform, providing APIs and services for subscription management, security insights, compliance monitoring, vulnerability assessment, patch management, content delivery, and automation. The Red Hat Hybrid Cloud Console exposes a comprehensive suite of REST APIs for managing RHEL systems at scale.

## APIs

### Red Hat Subscription Management API
API for managing RHEL subscriptions, entitlements, and system registrations. Enables automation of subscription lifecycle, system registration, and entitlement queries using OAuth 2.0 authentication.

- **Base URL:** `https://api.access.redhat.com/management/v1`
- **Documentation:** https://access.redhat.com/management/api/docs
- **Authentication:** OAuth 2.0 (offline token via Red Hat SSO)

### Red Hat Insights API
Predictive analytics and remediation service for RHEL systems. Provides advisor recommendations based on 20+ years of Red Hat support experience, covering security, performance, availability, and stability issues.

- **Base URL:** `https://console.redhat.com/api/insights/v1`
- **Documentation:** https://console.redhat.com/docs/api/insights

### Red Hat Security Data API
API for accessing security advisories, CVE data, bug fixes, and enhancement updates for Red Hat products. Enables automated vulnerability assessment and tracking of RHEL-relevant CVEs with severity filtering.

- **Base URL:** `https://access.redhat.com/hydra/rest/securitydata`
- **Documentation:** https://access.redhat.com/documentation/en-us/red_hat_security_data_api/1.0/

### Red Hat Insights Compliance API
API for assessing, monitoring, and reporting on security-policy compliance of RHEL systems. Based on SCAP, enables creation and management of compliance policies and reports.

- **Base URL:** `https://console.redhat.com/api/compliance/v2`
- **Documentation:** https://console.redhat.com/docs/api/compliance

### Red Hat Insights Vulnerability API
API for managing vulnerabilities on RHEL systems. Integrates with the Red Hat CVE database to assess outstanding CVEs and provide remediation guidance.

- **Base URL:** `https://console.redhat.com/api/vulnerability/v1`
- **Documentation:** https://console.redhat.com/docs/api/vulnerability

### Red Hat Insights Patch API
API for patch management of RHEL systems. Tracks applicable advisories and patches for registered systems.

- **Base URL:** `https://console.redhat.com/api/patch/v3`
- **Documentation:** https://console.redhat.com/docs/api/patch

### Red Hat Insights Host Inventory API
API for managing the inventory of RHEL systems registered with Red Hat Insights.

- **Base URL:** `https://console.redhat.com/api/inventory/v1`
- **Documentation:** https://console.redhat.com/docs/api/inventory

### Red Hat Insights Remediations API
API for creating and executing Ansible-based remediation playbooks for RHEL systems.

- **Base URL:** `https://console.redhat.com/api/remediations/v1`
- **Documentation:** https://console.redhat.com/docs/api/remediations

## OpenAPI Specifications

| API | Specification |
|-----|---------------|
| Red Hat Security Data API | [rhel-security-data-openapi.yml](openapi/rhel-security-data-openapi.yml) |
| Red Hat Subscription Management API | [rhel-subscription-management-openapi.yml](openapi/rhel-subscription-management-openapi.yml) |

## Capabilities

Naftiko capability definitions for AI-assisted RHEL management workflows:

| Capability | Description |
|------------|-------------|
| [Vulnerability Management](capabilities/vulnerability-management.yaml) | Unified CVE assessment, advisory lookup, and subscription tracking |

### Shared Definitions

| Definition | API |
|------------|-----|
| [security-data.yaml](capabilities/shared/security-data.yaml) | Red Hat Security Data API |
| [subscription-management.yaml](capabilities/shared/subscription-management.yaml) | Red Hat Subscription Management API |

## Rules

Spectral ruleset for validating RHEL API conventions:

- [rhel-rules.yml](rules/rhel-rules.yml)

## JSON Schemas

| Schema | Description |
|--------|-------------|
| [rhel-cve-schema.json](json-schema/rhel-cve-schema.json) | CVE record from the Security Data API |
| [rhel-system-schema.json](json-schema/rhel-system-schema.json) | Registered RHEL system record |

## JSON Structures

| Structure | Description |
|-----------|-------------|
| [rhel-cve-structure.json](json-structure/rhel-cve-structure.json) | Field-level documentation for CVE records |

## JSON-LD

| Context | Description |
|---------|-------------|
| [rhel-context.jsonld](json-ld/rhel-context.jsonld) | Linked data context for RHEL security and subscription entities |

## Examples

| Example | Description |
|---------|-------------|
| [rhel-get-cve-example.json](examples/rhel-get-cve-example.json) | Get CVE by ID request/response |
| [rhel-list-cves-example.json](examples/rhel-list-cves-example.json) | List CVEs with severity filter |

## Vocabulary

- [rhel-vocabulary.yml](vocabulary/rhel-vocabulary.yml) — Domain vocabulary for RHEL security, subscription, and compliance operations

## Links

- **Developer Portal:** https://developers.redhat.com/products/rhel
- **Hybrid Cloud Console:** https://console.redhat.com
- **Customer Portal:** https://access.redhat.com
- **GitHub (RedHatOfficial):** https://github.com/RedHatOfficial
- **GitHub (redhat-cop):** https://github.com/redhat-cop
- **Authentication Guide:** https://access.redhat.com/articles/3626371
