# US African Development Foundation (us-african-development-foundation)

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

The US African Development Foundation (USADF) is an independent federal agency established by Congress in 1980 to invest directly in African grassroots enterprises and social entrepreneurs. USADF provides grant capital of up to $250,000, capacity-building assistance, and convening opportunities to develop, grow, and scale African enterprises and entrepreneurs. USADF grant data is publicly accessible via the USASpending.gov API, and grant opportunities are posted to Grants.gov. Between 2019 and 2023, USADF awarded more than $141 million in grants to over 1,050 community enterprises in Africa, directly affecting 6.2 million people.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Federal Government
- International Development
- Africa
- Grants
- Nonprofit
- Economic Development

## Timestamps

- **Created:** 2024-11-20
- **Modified:** 2026-05-19

## APIs

### USADF Grants Data API

Access to USADF grant award data through the USASpending.gov API. Provides programmatic access to USADF grants, awards, recipients, and spending profiles as reported to the federal awards transparency system. USADF data is available via the USASpending API using the USADF agency identifier (CGAC 166).

- **Human URL:** [https://www.usaspending.gov/agency/african-development-foundation](https://www.usaspending.gov/agency/african-development-foundation)
- **Base URL:** `https://api.usaspending.gov`

#### Tags

- Grants
- Awards
- Spending
- Transparency
- Federal Awards

#### Properties

- [Documentation](https://api.usaspending.gov/docs/endpoints)
- [OpenAPI](openapi/usadf-grants-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usadf-grants-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usadf-grants-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/grants-api-award-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/grants-api-recipient-schema.json) — [JSON Schema](https://json-schema.org/specification)

### USADF Grant Opportunities API

Access to USADF grant opportunity listings through the Grants.gov API. USADF posts open grant solicitations on Grants.gov for African grassroots enterprises, cooperatives, and social entrepreneurs seeking funding. Grant amounts up to $250,000 for African-led development initiatives.

- **Human URL:** [https://www.grants.gov/search-grants?agencyCode=ADF](https://www.grants.gov/search-grants?agencyCode=ADF)
- **Base URL:** `https://apply07.grants.gov`

#### Tags

- Grant Opportunities
- Funding
- Applications
- Africa

#### Properties

- [Documentation](https://www.grants.gov/developers.html)
- [OpenAPI](openapi/usadf-grant-opportunities-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usadf-grant-opportunities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usadf-grant-opportunities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/grant-opportunities-api-opportunity-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/usadf)
- [Website](https://www.usadf.gov)
- [Portal](https://www.usaspending.gov/agency/african-development-foundation)
- [Data A P I](https://api.usaspending.gov)
- [Data A P I](https://www.grants.gov/search-grants?agencyCode=ADF)
- [GitHub Organization](https://github.com/usadf)
- [JSON-LD](json-ld/us-african-development-foundation-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/us-african-development-foundation-spectral-rules.yml)
- [Vocabulary](vocabulary/us-african-development-foundation-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
