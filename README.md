# University of Wisconsin-Madison (university-of-wisconsin-madison)

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
