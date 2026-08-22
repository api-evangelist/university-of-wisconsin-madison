# University of Wisconsin-Madison (university-of-wisconsin-madison)

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

The University of Wisconsin-Madison is a public land-grant research university in Madison, Wisconsin. Its Division of Information Technology (DoIT) runs a formal API Program on a UW-owned Google Apigee organization, fronted by a public developer portal at developer.wisc.edu, publishing eleven OpenAPI 3.0 contracts (245 operations) served from api.wisc.edu and mock.api.wisc.edu. This repository catalogs that public footprint as an APIs.json provider profile.

UW-Madison is one of the few institutions in this cohort that genuinely operates its own API program rather than pointing at a vendor's: every contract here declares a wisc.edu server and a wisc.edu contact, and no Figshare, Elsevier Pure, Ex Libris, Dataverse or Symplectic contract is attributed to the institution. Where a surface IS a vendor platform running under UW's name — Canvas LMS at canvas.wisc.edu — it is recorded as a tenant relationship, and the vendor's specification is deliberately not saved here.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-wisconsin-madison/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-wisconsin-madison-api-evangelist&utm_content=repo

## Type

- Index / Producer / 1st-Party
- Class: university — Public Research University

## Tags

University, Higher Education, Education, Public Research University, United States, Wisconsin, Big Ten, Association of American Universities, Identity, Identity Federation, Course Catalog, Research Repository, Student Information System, Human Resources, Finance, Curriculum

## APIs

All contracts below are `x-operator: institution` — retrieved from the developer portal's own
catalog API and verified to declare UW-Madison servers and contacts.

- **Person API** — Authoritative person/identity data. 47 operations, JSON:API, OAuth2 client credentials, gated. [OpenAPI](openapi/university-of-wisconsin-madison-person-api-openapi.yml) · Access: https://developer.wisc.edu/person-api/getting-access
- **Mock Person API** — Open mock of the Person API on mock.api.wisc.edu (47 operations). [OpenAPI](openapi/university-of-wisconsin-madison-mock-person-api-openapi.yml)
- **Mock Person API (Certificates)** — Certificate-auth variant, 39 operations. [OpenAPI](openapi/university-of-wisconsin-madison-mock-person-api-certificates-openapi.yml)
- **HR API** — Academic units, supervisory organizations, positions. 9 operations, gated. [OpenAPI](openapi/university-of-wisconsin-madison-hr-api-openapi.yml)
- **Mock HR API** — Open mock of the HR API. [OpenAPI](openapi/university-of-wisconsin-madison-mock-hr-api-openapi.yml)
- **Manifest API** — Groups and memberships, backed by Internet2 Grouper. 5 operations. [OpenAPI](openapi/university-of-wisconsin-madison-manifest-api-openapi.yml)
- **Mock Manifest API** — Open mock of the Manifest API. [OpenAPI](openapi/university-of-wisconsin-madison-mock-manifest-api-openapi.yml)
- **Finance API** — Awards, grants, gifts, funds, invoices, expense reports. 73 operations, the largest contract. [OpenAPI](openapi/university-of-wisconsin-madison-finance-api-openapi.yml)
- **Locations API** — Campus building and room reference data. 3 operations. [OpenAPI](openapi/university-of-wisconsin-madison-locations-api-openapi.yml)
- **Enterprise Billing API** — Service-provider billing transactions. 7 operations; published contract declares only a development server. [OpenAPI](openapi/university-of-wisconsin-madison-enterprise-billing-api-openapi.yml)
- **OAuth API** — Token endpoint for the whole gateway. [OpenAPI](openapi/university-of-wisconsin-madison-oauth-api-openapi.yml)
- **Public Course Search API** — UW-Madison's only openly callable API, unauthenticated, at public.enroll.wisc.edu. OpenAPI here is *probed*, not published by UW. [OpenAPI](openapi/university-of-wisconsin-madison-course-search-api-openapi.yml)
- **UW-Madison Identity Provider (Shibboleth)** — Institution-operated IdP serving SAML 2.0 metadata and OIDC discovery at login.wisc.edu.
- **MINDS@UW OAI-PMH Endpoint** — Live OAI-PMH 2.0 harvesting endpoint for the institutional repository, 13 metadata formats.
- **Curricular Data Model** — Generated Javadoc reference for the v1.5 data model; documentation only, no callable endpoint.
- **Canvas LMS** — `x-operator: tenant`. Instructure platform under UW's domain and IdP; the data is UW's, the contract is Instructure's.

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/university-of-wisconsin-madison-plans-pricing.yml](plans/university-of-wisconsin-madison-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-wisconsin-madison-rate-limits.yml](rate-limits/university-of-wisconsin-madison-rate-limits.yml)
- FinOps: [finops/university-of-wisconsin-madison-finops.yml](finops/university-of-wisconsin-madison-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.wisc.edu/
- Developer Portal: https://developer.wisc.edu/
- GitHub: https://github.com/UW-Madison-DoIT
- Source Code (API Publisher docs): https://git.doit.wisc.edu/interop/external-docs/api-publisher-documentation
- Documentation (KB): https://kb.wisc.edu/uw-apis/
- Identity Federation: https://login.wisc.edu/idp/shibboleth
- Course Catalog: https://public.enroll.wisc.edu/search
- Research Repository: https://minds.wisc.edu/
- AI Policy: https://it.wisc.edu/ai/generative-ai-uw-madison-use-policies/
- LinkedIn: https://www.linkedin.com/school/uw-madison/
- Twitter/X: https://twitter.com/UWMadison
- Status: https://outages.doit.wisc.edu/
- Authentication: Apigee + OAuth2 client credentials (https://api.wisc.edu/oauth/token)

## Notes

Re-profiled 2026-08-19 under the university pipeline, with operator attribution settled before any
contract was saved. Corrections made in this pass:

- **DARS API removed.** The 2026-06-03 review recorded its documentation URL as HTTP 200, but
  developer.wisc.edu is an Angular single-page app that returns a byte-identical 2,138-byte shell
  with status 200 for *every* URL, including deliberately bogus ones. DARS appears in neither the
  portal sitemap nor its API catalog. This was a soft-404, not a surface.
- **Source Code / Authentication pointers moved** off the now-archived `api-program` repository to
  the live `api-publisher-documentation` repository.
- **Status pointer corrected** from `www.outages.doit.wisc.edu` (connect failure) to
  `outages.doit.wisc.edu`.

Known limits: production APIs are gated behind manual per-product approval and a UW NetID, so
request/response behaviour could not be exercised — though UW publishes open mocks, which is why
the contracts remain fully readable. The estate declares zero OAuth scopes, and no contract carries
a license or terms of service. UW-Madison publishes no `llms.txt` and no RFC 9116 `security.txt`.
The LinkedIn school page returns HTTP 999 (anti-bot) but resolves in a browser.

## Maintainers

- Kin Lane — kin@apievangelist.com
