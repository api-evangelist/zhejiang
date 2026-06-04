# Zhejiang University (zhejiang)

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
