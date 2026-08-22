# Texas A&M University (texas-a-m-university)

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
