# Texas A&M University (texas-a-m-university)

Texas A&M University is a public land-grant research university in College Station, Texas, and the flagship of the Texas A&M University System, ranked #154 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an [APIs.json](https://apisjson.org) profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/texas-a-m-university/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=texas-a-m-university-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Geocoding, Library, United States

## APIs

- **TAMU GeoServices Geocoding API** — free geocoding, address standardization, and GIS data capture (REST + SOAP, v5; API key required). Docs: https://geoservices.tamu.edu/Services/Geocode/WebService/Details/ · Sign up: https://geoservices.tamu.edu/Signup/
- **UIN Services API** — TAMU System enterprise API to search/verify, create, and update Universal Identification Numbers; gated behind SEA DevOps subscription approval (x-api-key). Docs: https://it.tamus.edu/uinmanager/api/ · Portal: https://api-doc.sea.system.tamus.edu/

## Plans / Rate Limits / FinOps

- Plans: [plans/texas-a-m-university-plans-pricing.yml](plans/texas-a-m-university-plans-pricing.yml)
- Rate Limits: [rate-limits/texas-a-m-university-rate-limits.yml](rate-limits/texas-a-m-university-rate-limits.yml)
- FinOps: [finops/texas-a-m-university-finops.yml](finops/texas-a-m-university-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.tamu.edu
- Developer Portal: https://api-doc.sea.system.tamus.edu/
- GitHub (faculty/staff org): https://github.com/tamu-edu
- Source Code (Libraries): https://github.com/TAMULib
- LinkedIn: https://www.linkedin.com/school/texas-a-m-university/

## Notes

- Verification on 2026-06-03: the System API Developer Portal and GeoServices docs returned HTTP 200; the GeoServices v5 REST base URL resolved.
- The UIN Services API is documented but gated — no public base URL is published, so none is listed in apis.yml.
- TAMULib hosts deployable library open source (IIIF, DSpace, Vireo); these are software projects, not hosted public APIs, and are listed under Source Code.
- LinkedIn returns HTTP 999 to automated requests, which is expected anti-bot behavior and not an outage.
- No endpoints were fabricated; only confirmed URLs and properties are recorded.

## Maintainers

- Kin Lane — kin@apievangelist.com
