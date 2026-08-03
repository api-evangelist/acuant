# Acuant

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

Acuant is an identity verification and document authentication platform offering REST APIs and SDKs for ID capture, document authentication, biometric face matching, and passive liveness detection. Founded in 1999 as Card Scanning Solutions and acquired by GB Group plc (GBG) in 2021 for $736 million, Acuant's technology supports AML, KYC, and identity proofing workflows across financial services, healthcare, hospitality, and government sectors.

## APIs

- **AssureID Connect** — Document identity verification REST API supporting 3,400+ global document types (driver's licenses, passports, national IDs). Endpoints: `services.assureid.net`
- **FRM (Face Recognition and Matching)** — Biometric face match API comparing document photo to live selfie capture. Endpoints: `frm.acuant.net` (USA), `eu.frm.acuant.net` (EU), `aus.frm.acuant.net` (AUS)
- **Passive Liveness** — ISO/IEC 30107-3 compliant liveness detection with iBeta PAD Level 1 and Level 2 certification. Endpoints: `us.passlive.acuant.net`
- **ACAS (Cloud Authentication Service)** — Token issuance and credential management. Endpoints: `us.acas.acuant.net`, `eu.acas.acuant.net`, `aus.acas.acuant.net`
- **Ozone** — Digital identity trust scoring. Endpoints: `ozone.acuant.net`

## SDKs

- iOS SDK V11: https://github.com/Acuant/iOSSDKV11
- Android SDK V11: https://github.com/Acuant/AndroidSDKV11
- JavaScript Web SDK V11: https://github.com/Acuant/JavascriptWebSDKV11 (support mode through May 2026)

## Authentication

APIs use HTTP Basic Authentication (Base64-encoded `username:password`) over HTTPS, with bearer token support via JWT. A Subscription ID is required for biometric API calls.

## Links

- Website: https://www.acuant.com
- Integrations: https://www.acuant.com/integrations/
- GitHub: https://github.com/Acuant
- Status: https://status.acuant.net/
- Support: https://support.acuant.com
- Store: https://store.acuant.com
- LinkedIn: https://www.linkedin.com/company/acuant
