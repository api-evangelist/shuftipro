# Shufti Pro (shuftipro)

Shufti Pro is a global identity-verification provider offering KYC, KYB, and AML compliance through a single REST API. The Shufti Pro API runs document, facial biometric, address, consent, and AML/background-check verifications across 240+ countries and territories, with asynchronous callbacks, status retrieval, and data deletion.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/shuftipro/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/shuftipro/refs/heads/main/apis.yml)

## Tags

- Identity Verification
- KYC
- KYB
- AML
- Compliance

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Shufti Pro Verification API

Submits a verification request to api.shuftipro.com with one or more service objects - document, face, address, and consent - to run KYC identity verification across 10,000+ document types in 230+ countries.

- **Human URL:** [https://developers.shuftipro.com/docs/verification_endpoints/requests/](https://developers.shuftipro.com/docs/verification_endpoints/requests/)
- **Base URL:** `https://api.shuftipro.com`

#### Tags

- Verification
- Document
- Face
- Address
- Consent

#### Properties

- [Documentation](https://developers.shuftipro.com/docs/verification_endpoints/requests/)
- [API Reference](https://developers.shuftipro.com/docs/verification_endpoints/responses/)
- [OpenAPI](openapi/shuftipro-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shuftipro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shuftipro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shufti Pro KYB API

Know Your Business verification that fetches company registry records and corporate data, validates business existence, and resolves ultimate beneficial owners via the kyb service object on the verification endpoint.

- **Human URL:** [https://shuftipro.com/business-verification/](https://shuftipro.com/business-verification/)
- **Base URL:** `https://api.shuftipro.com`

#### Tags

- KYB
- Business Verification
- Registry

#### Properties

- [Documentation](https://shuftipro.com/business-verification/)
- [OpenAPI](openapi/shuftipro-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shuftipro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shuftipro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shufti Pro AML & Background Checks API

Screens an end-user's full name and date of birth against 1700+ global AML watchlists, sanctions, and PEP lists via the background_checks service object for ongoing compliance monitoring.

- **Human URL:** [https://developers.shuftipro.com/docs/verification_endpoints/requests/](https://developers.shuftipro.com/docs/verification_endpoints/requests/)
- **Base URL:** `https://api.shuftipro.com`

#### Tags

- AML
- Background Checks
- Watchlists
- Screening

#### Properties

- [Documentation](https://developers.shuftipro.com/docs/verification_endpoints/requests/)
- [OpenAPI](openapi/shuftipro-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shuftipro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shuftipro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shufti Pro Status API

Retrieves the current status, event, and proof URLs for a previously submitted verification by posting its reference to the /status endpoint, and deletes verification data via the /delete endpoint.

- **Human URL:** [https://developers.shuftipro.com/docs/verification_endpoints/responses/](https://developers.shuftipro.com/docs/verification_endpoints/responses/)
- **Base URL:** `https://api.shuftipro.com`

#### Tags

- Status
- Proofs
- Polling

#### Properties

- [Documentation](https://developers.shuftipro.com/docs/verification_endpoints/responses/)
- [OpenAPI](openapi/shuftipro-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shuftipro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shuftipro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shufti Pro Webhooks API

Server-to-server callbacks posted to a client-registered callback_url carrying verification events (verification.accepted, verification.declined, request.pending, request.deleted) with extracted data and a SHA256 response signature for validation.

- **Human URL:** [https://developers.shuftipro.com/docs/verification_methods/offsite](https://developers.shuftipro.com/docs/verification_methods/offsite)
- **Base URL:** `https://api.shuftipro.com`

#### Tags

- Webhooks
- Callbacks
- Notifications

#### Properties

- [Documentation](https://developers.shuftipro.com/docs/verification_methods/offsite)
- [OpenAPI](openapi/shuftipro-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/shuftipro)
- [LinkedIn](https://www.linkedin.com/company/shufti-pro)
- [Website](https://shuftipro.com)
- [Documentation](https://developers.shuftipro.com)
- [Plans](plans/shuftipro-plans-pricing.yml)
- [Rate Limits](rate-limits/shuftipro-rate-limits.yml)
- [Fin Ops](finops/shuftipro-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
