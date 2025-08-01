# Changelog MostFrequentLocation

## Table of Contents

- **[r2.1](#r21)**
- [r1.2](#r12)
- [r1.1](#r11)

**Please be aware that the project will have frequent updates to the main branch. There are no compatibility guarantees associated with code in any branch, including main, until it has been released. For example, changes may be reverted before a release is published. For the best results, use the latest published release.**

The below sections record the changes for each API version in each release as follows:

* for an alpha release, the delta with respect to the previous release
* for the first release-candidate, all changes since the last public release
* for subsequent release-candidate(s), only the delta to the previous release-candidate
* for a public release, the consolidated changes since the previous public release

# r2.1

This **public release** contains the definition and documentation of
* most-frequent-location 0.2.0-rc.1

The API definition(s) are based on
* Commonalities v0.6.0-rc.1
* Identity and Consent Management v0.4.0-rc.1

## most-frequent-location v0.2.0-rc.1

**most-frequent-location v0.2.0-rc.1 is the first release candidate of v2.0.0 of the Most Frequent Location API**

- API definition **with inline documentation**:
  - OpenAPI [YAML spec file](https://github.com/camaraproject/MostFrequentLocation/blob/r2.1/code/API_definitions/most-frequent-location.yaml)
  - [View it on ReDoc](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/MostFrequentLocation/r2.1/code/API_definitions/most-frequent-location.yaml&nocors)
  - [View it on Swagger Editor](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/MostFrequentLocation/r2.1/code/API_definitions/most-frequent-location.yaml)

### Changed
- Update `device` error codes by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/23
- Error model defined in Spring25 meta-release by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/23
- Update test plan with latest changes aligning with commonalities by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/23
- Align `info.description` section with Commonalities by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/23
- Update `x-correlator` format by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/23

### Removed
- AUTHENTICATION_REQUIRED and 5XX errors by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/23
- `INVALID_TOKEN_CONTEXT` error by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/23

**Full Changelog**: https://github.com/camaraproject/MostFrequentLocation/commits/r1.2...r2.1

# r1.2

## Release Notes

This release contains the definition and documentation of
* most-frequent-location v0.1.0

The API definition(s) are based on
* Commonalities v0.4.0
* Identity and Consent Management v0.2.1

## most-frequent-location v0.1.0

**most-frequent-location v0.1.0 is the 1st public release of the Most Frequent Location API**

- API definition **with inline documentation**:
  - OpenAPI [YAML spec file](https://github.com/camaraproject/MostFrequentLocation/blob/r1.2/code/API_definitions/most-frequent-location.yaml)
  - [View it on ReDoc](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/MostFrequentLocation/r1.2/code/API_definitions/most-frequent-location.yaml&nocors)
  - [View it on Swagger Editor](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/MostFrequentLocation/r1.2/code/API_definitions/most-frequent-location.yaml)

**Main changes**
* No new changes included from version v0.1.0-rc.1

**Full Changelog**: https://github.com/camaraproject/MostFrequentLocation/commits/r1.2

# r1.1
## Release Notes

This release contains the definition and documentation of
* most-frequent-location v0.1.0-rc.1

The API definition(s) are based on
* Commonalities v0.4.0
* Identity and Consent Management v0.2.1

## most-frequent-location v0.1.0-rc.1

**most-frequent-location v0.1.0-rc.1 is the 1st release candidate of the version 0.1.0**

- 0.1.0-rc.1 Most Frequent Location API definition **with inline documentation**:
  - OpenAPI [YAML spec file](https://github.com/camaraproject/MostFrequentLocation/blob/r1.1/code/API_definitions/most-frequent-location.yaml)
  - [View it on ReDoc](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/MostFrequentLocation/r1.1/code/API_definitions/most-frequent-location.yaml&nocors)
  - [View it on Swagger Editor](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/MostFrequentLocation/r1.1/code/API_definitions/most-frequent-location.yaml)

**Main changes**
* Initial version of the API

## Added
* Include initial proposal for Most Frequent Location API - Telefónica by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/6
* align-device-with-commonalities by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/9
* Corrections in yaml examples for request body and response errors by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/11
* Assumptions to use the API with postalCode but without countryName by @javier-carrocalabor in https://github.com/camaraproject/MostFrequentLocation/pull/15
* Include linter workflow files by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/16
* Include test plan by @fernandopradocabrillo in https://github.com/camaraproject/MostFrequentLocation/pull/13

## New Contributors
* @fernandopradocabrillo made their first contribution in https://github.com/camaraproject/MostFrequentLocation/pull/4
* @javier-carrocalabor made their first contribution in https://github.com/camaraproject/MostFrequentLocation/pull/15

**Full Changelog**: https://github.com/camaraproject/MostFrequentLocation/commits/r1.1
