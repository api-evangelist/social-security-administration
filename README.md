# Social Security Administration (social-security-administration)

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
