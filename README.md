# Acuant

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
