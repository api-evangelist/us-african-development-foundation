# US African Development Foundation (us-african-development-foundation)
The US African Development Foundation (USADF) is an independent federal agency established by Congress in 1980 to invest directly in African grassroots enterprises and social entrepreneurs. USADF provides grant capital of up to $250,000, capacity-building assistance, and convening opportunities to develop, grow, and scale African enterprises and entrepreneurs. USADF grant data is publicly accessible via the USASpending.gov API, and grant opportunities are posted to Grants.gov. Between 2019 and 2023, USADF awarded more than $141 million in grants to over 1,050 community enterprises in Africa, directly affecting 6.2 million people.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Federal Government, International Development, Africa, Grants, Nonprofit, Economic Development

## Timestamps

- **Created:** 2024-11-20
- **Modified:** 2026-05-03

## APIs

### USADF Grants Data API
Access to USADF grant award data through the USASpending.gov API. Provides programmatic access to USADF grants, awards, recipients, and spending profiles as reported to the federal awards transparency system. USADF data is available via the USASpending API using the USADF agency identifier (CGAC 166).

**Human URL:** [https://www.usaspending.gov/agency/african-development-foundation](https://www.usaspending.gov/agency/african-development-foundation)

#### Tags:

 - Grants, Awards, Spending, Transparency, Federal Awards

#### Properties

- [Documentation](https://api.usaspending.gov/docs/endpoints)
- [OpenAPI](openapi/usadf-grants-api-openapi.yml)
- [JSONSchema - Award](json-schema/grants-api-award-schema.json)
- [JSONSchema - Recipient](json-schema/grants-api-recipient-schema.json)

### USADF Grant Opportunities API
Access to USADF grant opportunity listings through the Grants.gov API. USADF posts open grant solicitations on Grants.gov for African grassroots enterprises, cooperatives, social entrepreneurs, and community organizations seeking funding. Grant amounts up to $250,000 for African-led development initiatives.

**Human URL:** [https://www.grants.gov/search-grants?agencyCode=ADF](https://www.grants.gov/search-grants?agencyCode=ADF)

#### Tags:

 - Grant Opportunities, Funding, Applications, Africa

#### Properties

- [Documentation](https://www.grants.gov/developers.html)
- [OpenAPI](openapi/usadf-grant-opportunities-api-openapi.yml)
- [JSONSchema - Opportunity](json-schema/grant-opportunities-api-opportunity-schema.json)

## Common Properties

- [Website](https://www.usadf.gov)
- [Portal](https://www.usaspending.gov/agency/african-development-foundation)
- [DataAPI](https://api.usaspending.gov)
- [DataAPI](https://www.grants.gov/search-grants?agencyCode=ADF)
- [GitHubOrganization](https://github.com/usadf)
- [JSONLD](json-ld/us-african-development-foundation-context.jsonld)
- [SpectralRules](rules/us-african-development-foundation-spectral-rules.yml)
- [Vocabulary](vocabulary/us-african-development-foundation-vocabulary.yaml)
- [NaftikoCapability - African Development Grants](capabilities/african-development-grants.yaml)
- [NaftikoCapability - Grants API (Shared)](capabilities/shared/grants-api.yaml)

## Features

| Name | Description |
|------|-------------|
| Grant Award Transparency | USADF grant award data publicly accessible via USASpending.gov API, including recipient, country, amount, and award period for all USADF grants. |
| Grant Opportunity Listings | USADF posts open grant solicitations on Grants.gov for African grassroots enterprises seeking funding up to $250,000. |
| Agency Spending Profile | Comprehensive USADF spending data accessible through USASpending.gov including account data, award breakdowns, and budget authority. |
| Recipient Data | Data on organizations receiving USADF grants across 24 African countries, including grant amounts, periods of performance, and program areas. |

## Use Cases

| Name | Description |
|------|-------------|
| Grant Transparency Research | Researchers and journalists accessing USADF grant award data through USASpending API to analyze funding patterns across African countries. |
| Grant Opportunity Discovery | African enterprises and NGOs finding and applying for USADF grant opportunities through Grants.gov listings. |
| Federal Spending Analysis | Policy analysts tracking USADF budget authority, obligations, and outlays through USASpending federal account data. |
| Development Impact Tracking | Development finance institutions and donors assessing USADF program reach and impact through award data and recipient profiles. |

## Integrations

| Name | Description |
|------|-------------|
| USASpending.gov | Federal awards transparency platform providing API access to all USADF grant awards, recipient data, and spending profiles. |
| Grants.gov | Federal grant opportunity portal where USADF posts open solicitations for African grassroots enterprise grants. |
| SAM.gov | System for Award Management where USADF grant recipients register to receive federal award funding. |
| FPDS-NG | Federal Procurement Data System tracking USADF contract and interagency agreement spending. |
| USAID OIG | USAID Office of Inspector General providing independent oversight of USADF grants administration and partnerships. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [USADF Grants Data API](openapi/usadf-grants-api-openapi.yml)
- [USADF Grant Opportunities API](openapi/usadf-grant-opportunities-api-openapi.yml)

### JSON Schema

- [Award](json-schema/grants-api-award-schema.json)
- [Recipient](json-schema/grants-api-recipient-schema.json)
- [Agency Award Summary](json-schema/grants-api-agencyawardsummary-schema.json)
- [Place of Performance](json-schema/grants-api-placeofperformance-schema.json)
- [Opportunity](json-schema/grant-opportunities-api-opportunity-schema.json)
- [Opportunity Search Response](json-schema/grant-opportunities-api-opportunitysearchresponse-schema.json)
- *(14 total schema files in json-schema/)*

### JSON Structure

- *(14 total structure files in json-structure/)*

### JSON-LD

- [US African Development Foundation Context](json-ld/us-african-development-foundation-context.jsonld)

### Examples

- [Award Example](examples/grants-api-award-example.json)
- [Recipient Example](examples/grants-api-recipient-example.json)
- [Opportunity Example](examples/grant-opportunities-api-opportunity-example.json)
- *(14 total example files in examples/)*

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Grants API](capabilities/shared/grants-api.yaml) — 5 operations for award search, award lookup, agency summary, recipient profiles, and geographic spending

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [African Development Grants](capabilities/african-development-grants.yaml) | Grants Data API, Grant Opportunities API | 7 | Development Finance Researcher, Grant Applicant, Transparency Analyst |

## Vocabulary

- [US African Development Foundation Vocabulary](vocabulary/us-african-development-foundation-vocabulary.yaml) — Unified taxonomy mapping 13 resources, 4 actions, 1 workflow, and 3 personas across operational and capability dimensions

## Rules

- [US African Development Foundation Spectral Rules](rules/us-african-development-foundation-spectral-rules.yml) — Rules across multiple categories enforcing USADF API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
