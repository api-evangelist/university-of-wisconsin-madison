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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of Wisconsin-Madison is a public land-grant research university ranked #46 in the QS World University Rankings 2025. Its Division of Information Technology (DoIT) runs a formal API Program with a public developer portal, an Apigee API gateway, OAuth2 authentication, and published JSON:API/OpenAPI standards. This repository catalogs that public developer/API footprint as an APIs.json provider profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-wisconsin-madison/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-wisconsin-madison-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Identity, Student Information System, Curriculum, Human Resources, United States

## APIs

- **Person API** — Authoritative person/identity data (gated; mock variant available). Docs: https://developer.wisc.edu/docs/person-api/1/overview · Access: https://developer.wisc.edu/person-api/getting-access
- **HR API** — Human resources data including academic units (mock published). Docs: https://developer.wisc.edu/docs/api-team-mock-hr-api/1/routes/academicUnits/get
- **Curricular Data Model API** — Courses and curriculum structures. Docs: https://wams.doit.wisc.edu/chub/curricular-data-model-1.5/apidocs/help-doc.html
- **DARS API** — Degree Audit Reporting System batch audit requests. Docs: https://developer.wisc.edu/docs/dars/1/types/DarsBatchAuditRequest

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/university-of-wisconsin-madison-plans-pricing.yml](plans/university-of-wisconsin-madison-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-wisconsin-madison-rate-limits.yml](rate-limits/university-of-wisconsin-madison-rate-limits.yml)
- FinOps: [finops/university-of-wisconsin-madison-finops.yml](finops/university-of-wisconsin-madison-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.wisc.edu/
- Developer Portal: https://developer.wisc.edu/
- GitHub: https://github.com/UW-Madison-DoIT
- Source Code (API Program): https://git.doit.wisc.edu/interop/external-docs/api-program
- LinkedIn: https://www.linkedin.com/school/uw-madison/
- Twitter/X: https://twitter.com/UWMadison
- Status: https://www.outages.doit.wisc.edu/
- Authentication: Apigee + OAuth2 (https://git.doit.wisc.edu/interop/external-docs/api-program/-/blob/main/practices/apigee.md)

## Notes

All cataloged entries map to documentation pages verified to return HTTP 200 on 2026-06-03. UW-Madison's production APIs are access-gated and require institutional approval; openly published mock APIs (Mock Person API, Mock HR API) support development. No base URLs or endpoints were fabricated — only confirmed documentation URLs are listed. The LinkedIn school page returns HTTP 999 (LinkedIn anti-bot) but resolves in a browser.

## Maintainers

- Kin Lane — kin@apievangelist.com
