# Unum

Unum Group is a leading Fortune 500 provider of financial protection benefits including disability insurance, life insurance, dental insurance, vision insurance, and critical illness coverage. Unum's developer platform offers APIs for HR system integration, eligibility management, leave and absence management, enrollment, and evidence of insurability processing.

**Developer Portal:** https://developer.unum.com/s/

**Website:** https://www.unum.com

## APIs

| API | Description |
|---|---|
| [Unum HR Connect API](openapi/unum-hr-connect-openapi.yml) | Real-time connection between Unum benefits and HR platforms (Workday, ADP, UKG) covering eligibility, enrollment, leave, EOI, and billing |
| Unum Benefits Enrollment API | Real-time enrollment elections and life event processing |
| Unum Leave and Absence Management API | FMLA, state leave, and STD request intake and status tracking |

## OpenAPI Specifications

| Spec | Description |
|---|---|
| [unum-hr-connect-openapi.yml](openapi/unum-hr-connect-openapi.yml) | Unum HR Connect API covering eligibility, enrollment, leave, EOI, and billing |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [unum-rules.yml](rules/unum-rules.yml) | Spectral ruleset enforcing Unum API naming conventions, pagination, security, and response envelope patterns |

## Naftiko Capabilities

### Shared Definitions

| File | APIs Covered |
|---|---|
| [shared/hr-connect.yaml](capabilities/shared/hr-connect.yaml) | Unum HR Connect API (eligibility, enrollment, leave, EOI, billing) |

### Workflow Capabilities

| Workflow | Description | Tools |
|---|---|---|
| [benefits-administration.yaml](capabilities/benefits-administration.yaml) | End-to-end HR benefits administration — eligibility, enrollment, leave, EOI, and billing | 15 tools |

## JSON Schemas

| Schema | Description |
|---|---|
| [unum-member-schema.json](json-schema/unum-member-schema.json) | Member eligibility and coverage record |
| [unum-leave-request-schema.json](json-schema/unum-leave-request-schema.json) | Leave and absence request |

## JSON Structure

| Structure | Description |
|---|---|
| [unum-member-structure.json](json-structure/unum-member-structure.json) | Field-level documentation for the Member resource |

## JSON-LD

| Context | Description |
|---|---|
| [unum-context.jsonld](json-ld/unum-context.jsonld) | Linked data context mapping Unum resources to schema.org |

## Examples

| Example | Description |
|---|---|
| [unum-list-eligible-members-example.json](examples/unum-list-eligible-members-example.json) | GET /eligibility/members request and response |
| [unum-submit-leave-request-example.json](examples/unum-submit-leave-request-example.json) | POST /leave/requests request and response |
| [unum-submit-eoi-example.json](examples/unum-submit-eoi-example.json) | POST /eoi/submissions request and response |

## Vocabulary

| File | Description |
|---|---|
| [unum-vocabulary.yml](vocabulary/unum-vocabulary.yml) | Domain vocabulary for Unum benefits administration including insurance products, leave types, and HR integration concepts |

## Links

- **Website:** https://www.unum.com
- **Developer Portal:** https://developer.unum.com/s/
- **HR Connect Integration:** https://www.unum.com/employers/hr-trends/api-integration-with-hr-systems
- **Blog:** https://www.unum.com/employers/hr-trends

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
