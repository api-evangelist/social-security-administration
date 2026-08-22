# Social Security Administration (social-security-administration)

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

The Social Security Administration (SSA) is a U.S. federal agency that administers Social Security programs including retirement, disability (SSDI), and survivor benefits. SSA's Developer Support portal provides APIs for locating field offices and resident stations, accessing open data on OASDI beneficiary statistics, and verifying Social Security Numbers through the eCBSV program.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/social-security-administration/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/social-security-administration/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Social Security
- Government API
- Open Data
- OASDI
- Disability Benefits
- Retirement Benefits

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### SSA Field Office Address API

Provides location, address, telephone numbers, and office hours for Social Security Administration Field Offices across the United States. Uses the Esri ArcGIS Online platform as a RESTful Feature Service.

- **Human URL:** [https://www.ssa.gov/developer/api/FO_Address_Data_AppDevs.htm](https://www.ssa.gov/developer/api/FO_Address_Data_AppDevs.htm)

#### Tags

- Field Offices
- Location Services
- Government Data
- Open Data

#### Properties

- [Documentation](https://www.ssa.gov/developer/api/FO_Address_Data_AppDevs.htm)
- [OpenAPI](openapi/ssa-field-office-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ssa-field-office.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssa-field-office.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Arc G I S  Feature  Service](https://services6.arcgis.com/zFiipv75rloRP5N4/ArcGIS/rest/services/Office_Points/FeatureServer/1)

### SSA Resident Station Address API

Provides location, address, telephone numbers, and office hours for Social Security Administration Resident Stations — smaller SSA offices that serve rural communities. Uses the Esri ArcGIS Online platform as a RESTful Feature Service.

- **Human URL:** [https://www.ssa.gov/developer/api/RS_Address_Data_AppDevs.htm](https://www.ssa.gov/developer/api/RS_Address_Data_AppDevs.htm)

#### Tags

- Resident Stations
- Location Services
- Government Data
- Open Data

#### Properties

- [Documentation](https://www.ssa.gov/developer/api/RS_Address_Data_AppDevs.htm)
- [OpenAPI](openapi/ssa-resident-station-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ssa-resident-station.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssa-resident-station.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Arc G I S  Feature  Service](https://services6.arcgis.com/zFiipv75rloRP5N4/arcgis/rest/services/SSA_Resident_Station_Information/FeatureServer)

### SSA OASDI Open Data API

Provides statistics on Old Age, Survivors, and Disability Insurance (OASDI) beneficiaries including counts by state, total population data, and benefit payment statistics. Available through SSA's open data portal and Esri Feature Services.

- **Human URL:** [https://www.ssa.gov/data/OASDIBeneficiariesbyState.htm](https://www.ssa.gov/data/OASDIBeneficiariesbyState.htm)

#### Tags

- OASDI
- Beneficiary Statistics
- Open Data
- Benefits Data

#### Properties

- [Documentation](https://www.ssa.gov/data/OASDIBeneficiariesbyState.htm)
- [Open  Data  Portal](https://www.ssa.gov/data/)
- [Postman Collection](collections/ssa-field-office.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssa-field-office.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ssa-resident-station.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssa-resident-station.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SSA eCBSV Verification API

The Electronic Consent Based SSN Verification (eCBSV) Service allows financial institutions to verify that a provided Social Security Number, name, and date of birth match SSA records, with consent from the individual. Access is restricted to eligible financial institutions.

- **Human URL:** [https://www.ssa.gov/dataexchange/eCBSV/](https://www.ssa.gov/dataexchange/eCBSV/)

#### Tags

- SSN Verification
- Identity Verification
- Financial Services
- Consent Based

#### Properties

- [Documentation](https://www.ssa.gov/dataexchange/eCBSV/technical_information.html)
- [C B S V  Web  Service](https://www.ssa.gov/cbsv/webservice.html)
- [Postman Collection](collections/ssa-field-office.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssa-field-office.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ssa-resident-station.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssa-resident-station.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/ssa)
- [Website](https://www.ssa.gov/)
- [Developer  Portal](https://www.ssa.gov/developer/)
- [Open  Data  Portal](https://www.ssa.gov/data/)
- [Open  Data  Inventory](https://www.ssa.gov/data/Open-Data-Inventory-Information.html)
- [Data.gov  Organization](https://catalog.data.gov/organization/ssa-gov)
- [J S O N  Schema](json-schema/ssa-field-office-schema.json)
- [J S O N  Schema](json-schema/ssa-resident-station-schema.json)
- [J S O N  Structure](json-structure/ssa-office-structure.json)
- [J S O N- L D  Context](json-ld/ssa-context.jsonld)
- [Vocabulary](vocabulary/ssa-vocabulary.yml)
- [Examples](examples/ssa-field-office-query-example.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
