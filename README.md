# Zhejiang University (zhejiang)

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

Zhejiang University (ZJU) is a comprehensive public research university in Hangzhou, China, ranked #44 in the QS World University Rankings 2025. This repository catalogs ZJU's confirmable public developer/API footprint as an [APIs.json](https://apisjson.org) profile. ZJU does not publish a centralized public developer portal or documented open API program; the verifiable surface is limited to identity/SSO infrastructure and a community-run open-source mirror.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/zhejiang/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=zhejiang-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, China, Identity, SSO

## APIs

- **Unified Identity Authentication (CAS / SSO)** — campus single sign-on gateway. Docs: https://zjuam.zju.edu.cn/cas/login?locale=en
- **Shibboleth Identity Provider (SAML)** — federated SAML 2.0 IdP. Docs: https://idp.zju.edu.cn/idp/shibboleth
- **ZJU Open Source Software Mirrors** — community (LUG@ZJU) software mirror service. Docs: https://mirrors.zju.edu.cn/

These are infrastructure/federation endpoints, not documented self-service application APIs.

## Plans

- [plans/zhejiang-plans-pricing.yml](plans/zhejiang-plans-pricing.yml)

## Rate Limits

- [rate-limits/zhejiang-rate-limits.yml](rate-limits/zhejiang-rate-limits.yml)

## FinOps

- [finops/zhejiang-finops.yml](finops/zhejiang-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.zju.edu.cn/english/
- GitHub (LUG@ZJU): https://github.com/zjulug
- LinkedIn: https://www.linkedin.com/school/zhejiang-university/
- Authentication: https://zjuam.zju.edu.cn/cas/login?locale=en

## Notes

All endpoints were probed live on 2026-06-03; only URLs that resolved are cataloged. No application endpoints were fabricated. No public developer portal, open-data portal, course/SIS API, library API (Alma/Primo/IIIF/OAI-PMH), or institutional-repository REST API was found. Numerous ZJU research-lab GitHub organizations exist (e.g. ZJU-SEL, ZJU-Robotics-Lab, zjulug) but represent project-specific code rather than an institutional API program. The LinkedIn page returns HTTP 999 due to LinkedIn's bot-blocking, not because the page is absent.

## Maintainers

- Kin Lane — kin@apievangelist.com
