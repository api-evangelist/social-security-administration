# Social Security Administration

The Social Security Administration (SSA) is a U.S. federal agency that administers Social Security programs including retirement, disability (SSDI), and survivor benefits. SSA's Developer Support portal provides APIs for locating field offices and resident stations, accessing open data on OASDI beneficiary statistics, and verifying Social Security Numbers through the eCBSV program.

## APIs

### SSA Field Office Address API

Locations, addresses, phone numbers, and hours for SSA Field Offices nationwide via ArcGIS Feature Service (no auth required).

- **Documentation:** https://www.ssa.gov/developer/api/FO_Address_Data_AppDevs.htm
- **ArcGIS Service:** https://services6.arcgis.com/zFiipv75rloRP5N4/ArcGIS/rest/services/Office_Points/FeatureServer/1
- **OpenAPI Spec:** [openapi/ssa-field-office-openapi.yml](openapi/ssa-field-office-openapi.yml)

### SSA Resident Station Address API

Locations, addresses, phone numbers, and hours for SSA Resident Stations serving rural communities via ArcGIS Feature Service.

- **Documentation:** https://www.ssa.gov/developer/api/RS_Address_Data_AppDevs.htm
- **ArcGIS Service:** https://services6.arcgis.com/zFiipv75rloRP5N4/arcgis/rest/services/SSA_Resident_Station_Information/FeatureServer
- **OpenAPI Spec:** [openapi/ssa-resident-station-openapi.yml](openapi/ssa-resident-station-openapi.yml)

### SSA OASDI Open Data API

Statistics on OASDI beneficiaries by state and total population.

- **Documentation:** https://www.ssa.gov/data/OASDIBeneficiariesbyState.htm
- **Open Data Portal:** https://www.ssa.gov/data/

### SSA eCBSV Verification API

Electronic Consent Based SSN Verification for financial institutions.

- **Documentation:** https://www.ssa.gov/dataexchange/eCBSV/technical_information.html
- **Access:** Restricted to eligible financial institutions

## Artifacts

| Type | File |
|------|------|
| OpenAPI (Field Offices) | [openapi/ssa-field-office-openapi.yml](openapi/ssa-field-office-openapi.yml) |
| OpenAPI (Resident Stations) | [openapi/ssa-resident-station-openapi.yml](openapi/ssa-resident-station-openapi.yml) |
| JSON Schema (Field Office) | [json-schema/ssa-field-office-schema.json](json-schema/ssa-field-office-schema.json) |
| JSON Schema (Resident Station) | [json-schema/ssa-resident-station-schema.json](json-schema/ssa-resident-station-schema.json) |
| JSON Structure | [json-structure/ssa-office-structure.json](json-structure/ssa-office-structure.json) |
| JSON-LD Context | [json-ld/ssa-context.jsonld](json-ld/ssa-context.jsonld) |
| Spectral Rules | [rules/ssa-rules.yml](rules/ssa-rules.yml) |
| Vocabulary | [vocabulary/ssa-vocabulary.yml](vocabulary/ssa-vocabulary.yml) |
| Example: Field Office Query | [examples/ssa-field-office-query-example.json](examples/ssa-field-office-query-example.json) |

## Links

- **Website:** https://www.ssa.gov/
- **Developer Portal:** https://www.ssa.gov/developer/
- **Open Data Portal:** https://www.ssa.gov/data/
- **Data.gov:** https://catalog.data.gov/organization/ssa-gov

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

