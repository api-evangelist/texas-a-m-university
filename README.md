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

- University / Public Research University / Index / Consumer / 3rd-Party

## Tags

University, Higher Education, Education, United States, Texas, Public Research University, Land Grant, Research, Research Data, Research Repository, Identity Federation, Geospatial, Geocoding, Open Data, Library, Course Catalog, Campus Life, Research Computing

## Who operates what

A university is a federation of buyers, so every surface below carries an operator. `institution`
means Texas A&M runs the thing the contract describes. `tenant` means Texas A&M's data on a vendor's
platform — the relationship is real, the contract is not theirs. `registry` and `federation` are
memberships, which are facts about the institution and are never deleted to tidy up a shared host.

### Institution-operated

- **Texas A&M GeoServices Geocoding API** (`institution`) — free, documented, self-service geocoding
  and address normalisation, v5.0.0, up to 172 output fields. API key travels as a query parameter.
  [OpenAPI](openapi/texas-a-m-university-geoservices-geocoding-openapi.yml) ·
  [Docs](https://geoservices.tamu.edu/Services/Geocode/WebService/Details/) ·
  [Sign up](https://geoservices.tamu.edu/Signup/)
- **Aggie Map Dining Locations API** (`institution`) — GeoJSON feed of 54 campus dining locations
  with live open/closed state, on `api.aggiemap.tamu.edu`. Undocumented application backend.
  [OpenAPI](openapi/texas-a-m-university-aggiemap-dining-openapi.yml)
- **Campus Micromobility Vehicle Positions** (`institution`) — 3,300 live vehicle positions as
  GeoJSON from `veoride.geoservices.tamu.edu`. Geometry only; properties are empty.
  [OpenAPI](openapi/texas-a-m-university-campus-micromobility-openapi.yml)
- **Texas A&M IT ArcGIS REST Services** (`institution`) — public Esri ArcGIS Server at
  `gis.it.tamu.edu` (mirrored at `gis.tamu.edu`), currentVersion 11.5, seven folders of campus base
  maps, ADA routes, construction, transit and event-flow layers. The deployment is Texas A&M's; the
  REST contract is Esri's and is deliberately not saved here.
- **OAKTrust Institutional Repository — OAI-PMH** (`institution`) — working OAI-PMH 2.0 endpoint at
  `oaktrust.library.tamu.edu/server/oai/request`. The Identify response names Texas A&M Libraries'
  own help desk and no vendor at all.
- **Shibboleth Identity Provider metadata** (`institution`) — SAML 2.0 EntityDescriptor published
  unauthenticated from `idp.tamu.edu`.
  [OpenAPI](openapi/texas-a-m-university-identity-federation-openapi.yml)
- **UIN Services API** (`institution`, gated) — Texas A&M University System enterprise identity API.
  Documented in prose; no base URL, no specification, and no unauthenticated portal discovery route
  responds. Inventoried, never described as callable.

### Tenant

- **Texas A&M Course Catalog** — Leepfrog CourseLeaf at `catalog.tamu.edu`. Its `/ribbit/` course
  route returns XML, but the endpoint shape is shared by every CourseLeaf customer.
- **Canvas** — `canvas.tamu.edu` is a CNAME to `texasam-vanity.instructure.com`. The LMS API and any
  LTI conformance are Instructure's.

### Registry and federation

- **DataCite** — provider `CXAU` "Texas A&M Libraries", carrying ROR id `01f5ytq51`; repository
  client `TDL.TAMU`; DOI prefix 10.21423; 8,925 DOIs.
- **Crossref** — member 14385 "Texas A&M University Libraries", same prefix 10.21423, 7,464 DOIs.
- **ROR** — `https://ror.org/01f5ytq51`.
- **InCommon** — entityID `urn:mace:incommon:tamu.edu`, resolvable through InCommon MDQ and carried
  into eduGAIN.

## What is not here

- **No open-data portal.** `data.tamu.edu` resolves in DNS (CNAME `weasel.tamu.edu`) but every HTTPS
  connection timed out.
- **No llms.txt** on `www.tamu.edu`.
- **No public course, registrar or timetable API.** The catalog is a CourseLeaf tenancy.
- **No enterprise API catalog without an account.** Every discovery route tried on
  `api-doc.sea.system.tamus.edu` returned 404.
- **Three hosts are live but unreadable by us** — `oaktrust.library.tamu.edu/server/api`,
  `scholars.library.tamu.edu` and `hprc.tamu.edu` return a Cloudflare 403 challenge to a browser
  User-Agent. That is a fact about our access, not about Texas A&M.

## Artifacts

- OpenAPI: [openapi/](openapi/) (pristine pre-refine copies in [openapi/_original/](openapi/_original/))
- JSON Schema: [json-schema/](json-schema/)
- Examples: [examples/](examples/)
- Authentication: [authentication/texas-a-m-university-authentication.yml](authentication/texas-a-m-university-authentication.yml)
- Errors: [errors/texas-a-m-university-errors.yml](errors/texas-a-m-university-errors.yml)
- Conformance (education regime domain standards): [conformance/texas-a-m-university-domain-standards.yml](conformance/texas-a-m-university-domain-standards.yml)
- Plans: [plans/texas-a-m-university-plans-pricing.yml](plans/texas-a-m-university-plans-pricing.yml)
- Rate Limits: [rate-limits/texas-a-m-university-rate-limits.yml](rate-limits/texas-a-m-university-rate-limits.yml)
- FinOps: [finops/texas-a-m-university-finops.yml](finops/texas-a-m-university-finops.yml)
- Security: [security/](security/)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://www.tamu.edu
- Developer Portal: https://api-doc.sea.system.tamus.edu/
- GitHub (faculty/staff org): https://github.com/tamu-edu
- Source Code (Libraries): https://github.com/TAMULib
- Library: https://library.tamu.edu/
- Course Catalog: https://catalog.tamu.edu/
- Identity Federation: https://mdq.incommon.org/entities/urn%3Amace%3Aincommon%3Atamu.edu
- Research Computing: https://hprc.tamu.edu/
- AI Policy: https://ai.tamu.edu/teach-with-ai/use-guidelines-and-ethics.html
- AI Tooling: https://it.tamu.edu/ai-services/index.html
- LinkedIn: https://www.linkedin.com/school/texas-a-m-university/

## Notes

- Every surface in this repository was fetched on 2026-09-01 and given a status code before it was
  written down. Provenance is stamped on every artifact: `method: probed` where a live response was
  observed, `method: derived` where a schema was read from published documentation.
- **GeoServices returns HTTP 200 for failed calls** and carries the real 401/402 inside the JSON
  body, so transport-level monitoring cannot see its failures. Recorded in `errors/`.
- **The v4 SOAP WSDL that Texas A&M's own documentation advertises does not resolve** — it
  302-redirects to `/Support/ServerError.aspx`. Recorded as a live defect, not catalogued as a WSDL.
- TAMULib hosts deployable library open source (IIIF, DSpace, Vireo); these are software projects,
  not hosted public APIs, and are listed under Source Code.
- LinkedIn returns HTTP 999 to automated requests, which is expected anti-bot behavior, not an outage.
- No endpoints were fabricated; only confirmed URLs and properties are recorded.

## Maintainers

- Kin Lane — kin@apievangelist.com
