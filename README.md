# Absence.io (absence-io)
Absence.io is an innovative and efficient leave management software that simplifies the process of tracking and managing employee absences. It provides a centralized platform for both employees and managers to easily request, approve, and track time-off requests. The REST API v2 allows integration with absences, users, allowances, departments, locations, reason types, and timespans using Hawk authentication.

**URL:** [https://www.absence.io/](https://www.absence.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Absences, Employees, Leave Management, HR

## Timestamps

- **Created:** 2025-02-17
- **Modified:** 2026-04-19

## APIs

### Absence.io API
Absence.io REST API v2 allows seamless integration of absence management features into software applications. Retrieve, create, update, and delete records for absences, users, allowances, departments, locations, reason types, and timespans. All requests and responses use JSON format with Hawk authentication.

**Human URL:** [https://www.absence.io/](https://www.absence.io/)

#### Tags:

 - Absences, Employees, Leave Management

#### Properties

- [Documentation](https://docs.absence.io/)
- [Authentication](https://docs.absence.io/#authentication)
- [OpenAPI](openapi/absence-io-openapi.yml)
- [SDK - Node.js](https://www.npmjs.com/package/absence.io)
- [JSONSchema - Absence](json-schema/absence-schema.json)
- [JSONSchema - User](json-schema/user-schema.json)
- [JSONSchema - Allowance](json-schema/allowance-schema.json)

## Common Properties

- [Pricing](https://www.absence.io/pricing/pricing-packages/)
- [Authentication](https://docs.absence.io/#authentication)
- [Blog](https://blog.absence.io/en/)
- [Partners](https://promo.absence.io/partner-program)
- [TermsOfService](https://www.absence.io/terms-and-conditions/)
- [PrivacyPolicy](https://www.absence.io/privacy-notice/)

## Features

| Name | Description |
|------|-------------|
| Absence Management | Create, approve, and track employee vacation, sick leave, and other absence types through a centralized platform. |
| Leave Allowances | Configure and track annual leave allowances per employee, including carryover management. |
| Approval Workflows | Configurable approval workflows for absence requests with manager notifications and audit trail. |
| Organizational Structure | Support for departments, locations, and teams to reflect your organization's hierarchy. |
| Reason Types | Customizable absence reason types (vacation, sick leave, parental leave, etc.) with color coding. |
| Working Time Configurations | Define timespans with hours per day and days per week for accurate absence calculation. |
| REST API v2 | Full REST API for integrating absence management with ERP, HRIS, and other business systems using Hawk authentication. |

## Use Cases

| Name | Description |
|------|-------------|
| ERP Integration | Integrate absence data with ERP systems to automatically reflect employee availability and costs. |
| HRIS Sync | Sync employee records between Absence.io and HR information systems to maintain a single source of truth. |
| Payroll Processing | Use absence and allowance data to calculate accurate payroll deductions and entitlements. |
| Capacity Planning | Query team absence data to plan project staffing and identify scheduling conflicts. |
| Absence Reporting | Generate custom reports on absence patterns, allowance usage, and team availability. |
| Custom Dashboards | Pull absence and allowance data into custom HR dashboards and analytics tools. |

## Integrations

| Name | Description |
|------|-------------|
| Slack | Integration with Slack for absence request notifications and team visibility. |
| Atlassian Jira | Integration with Jira for project planning with awareness of team availability. |
| SharePoint | Integration with SharePoint for absence calendar sharing and team visibility. |
| Google Calendar | Sync absence records to Google Calendar for team scheduling visibility. |
| Redmine | Integration with Redmine project management for resource planning. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Absence.io API](openapi/absence-io-openapi.yml)

### JSON Schema

- [Absence](json-schema/absence-schema.json)
- [User](json-schema/user-schema.json)
- [Allowance](json-schema/allowance-schema.json)
- [Department](json-schema/department-schema.json)
- [Location](json-schema/location-schema.json)
- [Reason Type](json-schema/reason-type-schema.json)
- [Timespan](json-schema/timespan-schema.json)

### JSON Structure

- [Absence](json-structure/absence-structure.json)
- [User](json-structure/user-structure.json)
- [Allowance](json-structure/allowance-structure.json)
- [Department](json-structure/department-structure.json)
- [Location](json-structure/location-structure.json)
- [Reason Type](json-structure/reason-type-structure.json)
- [Timespan](json-structure/timespan-structure.json)

### JSON-LD

- [Absence.io Context](json-ld/absence-io-context.jsonld)

### Examples

- [Absence Example](examples/absence-example.json)
- [User Example](examples/user-example.json)
- [Allowance Example](examples/allowance-example.json)
- [Department Example](examples/department-example.json)
- [Location Example](examples/location-example.json)
- [Reason Type Example](examples/reason-type-example.json)
- [Timespan Example](examples/timespan-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Absence.io API](capabilities/shared/absence-io.yaml) — 11 operations for absence CRUD, users, allowances, departments, locations, reason types, and timespans

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Absence Management](capabilities/absence-management.yaml) | Absence.io API | 11 | HR Manager, Payroll Processor, Integration Developer |

## Vocabulary

- [Absence.io Vocabulary](vocabulary/absence-io-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 5 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Absence.io Spectral Rules](rules/absence-io-spectral-rules.yml) — 28 rules across 12 categories enforcing Absence.io API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
