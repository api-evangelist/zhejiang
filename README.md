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

Zhejiang University (浙江大学, ZJU) is a comprehensive public research university in Hangzhou, China — a C9 League and Double First-Class institution. This repository catalogs ZJU's confirmable public programmable footprint as an [APIs.json](https://apisjson.org) profile, re-profiled on 2026-08-19 under the API Evangelist **university pipeline**, which settles *who operates* each surface before saving any contract.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/zhejiang/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=zhejiang-api-evangelist&utm_content=repo

## Type

- University / Public Research University — Index / Consumer / 3rd-Party

## Tags

University, Higher Education, Education, Research, China, C9 League, Double First-Class, Identity Federation, Single Sign-On, Open Source Mirror, Library

## Surfaces — every one operated by the institution

All three are on ZJU's own registrable domain `zju.edu.cn`. **No vendor contract is attributed to ZJU in this repository**, and no tenant relationship on a research-data platform (Figshare, Pure, Dataverse, DSpace, Symplectic) exists to record — none was found.

- **Open Source Software Mirror Service** (`mirrors.zju.edu.cn`) — 浙江大学开源软件镜像站, maintained by the ZJU Supercomputing Team (ZJUSCT), contact `mirrors@zju.edu.cn`. Publishes a real machine-readable service catalog at [`/mirrorz.json`](https://mirrors.zju.edu.cn/mirrorz.json) implementing the MirrorZ data contract v1.7 — 63 mirrored repositories, anonymous read. **This is the only genuinely machine-readable API-shaped contract ZJU operates itself.** ZJU publishes no OpenAPI for it; the [OpenAPI](openapi/zhejiang-mirror-service-openapi.yml) and [JSON Schema](json-schema/zhejiang-mirrorz-document.json) here were *derived* by API Evangelist from the live response and are marked as such.
- **Shibboleth Identity Provider** (`idp.zju.edu.cn`) — SAML 2.0 IdP, entityID `https://idp.zju.edu.cn/idp/shibboleth`, registered in **CARSI** and interfederated through **eduGAIN** since 2020-01-31. See [identity-federation/](identity-federation/zhejiang-identity-federation.yml). Caveat recorded in full: the metadata ZJU serves at its own entityID is the unmodified Shibboleth installer artifact, `validUntil` 2020-01-29 — expired — with no Organization or ContactPerson block.
- **Unified Identity Authentication** (`zjuam.zju.edu.cn`) — CAS single sign-on. Interactive web login only; no published API contract.

## Gated, not absent

- `opac.zju.edu.cn` returns **403** with a human-readable notice that the library catalog has been withdrawn from the public internet in favour of WebVPN and the ZJU DingTalk mobile library.
- `zdbk.zju.edu.cn` (本科教学管理信息服务平台) is a login-only vendor teaching-management system on a ZJU host.

## Not found (probed, not assumed)

No central developer portal, no open data portal, no institution-operated OAI-PMH endpoint, no research data repository, no OpenAPI/AsyncAPI/GraphQL, no MCP server, no agent card, no `robots.txt` / `security.txt` / `llms.txt` on `www.zju.edu.cn`. `libweb.zju.edu.cn/oai` returns HTTP 200 with a CMS error body — a **soft-404**, deliberately not credited as OAI-PMH.

## Artifacts

- [openapi/](openapi/) (+ [`_original/`](openapi/_original/)) · [json-schema/](json-schema/) · [examples/](examples/)
- [identity-federation/](identity-federation/) · [conformance/](conformance/) · [authentication/](authentication/) · [scopes/](scopes/)
- [errors/](errors/) · [rules/](rules/) · [vocabulary/](vocabulary/) · [lifecycle/](lifecycle/) · [json-ld/](json-ld/)
- [plans/](plans/zhejiang-plans-pricing.yml) · [rate-limits/](rate-limits/zhejiang-rate-limits.yml) · [finops/](finops/zhejiang-finops.yml) · [security/](security/)

Every artifact carries `generated`, `method` (`searched` | `derived` | `probed`) and `source`. Nothing here is credited to ZJU as though ZJU published it.

## Domain standard conformance (Kin Score `education` regime)

| Standard | Status | Evidence |
|---|---|---|
| `shibboleth` | conformant | SAML metadata at the entityID; Shibboleth-native SSO binding advertised |
| `saml` | conformant | SAML 2.0 SSO/SLO/ArtifactResolution/AttributeQuery endpoints; eduGAIN registration via CARSI |
| `oai-pmh` | **not found** | `libweb.zju.edu.cn/oai?verb=Identify` soft-404s |
| `scim`, `lti`, `oneroster`, `ed-fi`, `caliper`, `qti`, `orcid`, `datacite`, `crossref` | not found | see [conformance/](conformance/zhejiang-education-standards.yml) |

## GitHub

- ZJU Supercomputing Team: https://github.com/ZJUSCT
- LUG@ZJU: https://github.com/zjulug

Numerous ZJU research-lab GitHub organizations exist (ZJU-SEL, ZJU-Robotics-Lab, ZJU-FAST-Lab and others); they hold project-specific code, not an institutional API program.

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Notes

All endpoints were probed live on 2026-08-19 with a browser User-Agent; status codes are recorded in `x-coverage.evidence` in `apis.yml`. Only URLs that resolved are cataloged, and no application endpoints were fabricated. The LinkedIn page returns HTTP 999 because of LinkedIn's bot-blocking, not because the page is absent.

## Maintainers

- Kin Lane — kin@apievangelist.com
