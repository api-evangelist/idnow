# IDnow (idnow)

IDnow is a European identity-verification platform offering automated (AutoIdent) and human-assisted (VideoIdent) KYC/identity proofing, plus eID and qualified electronic signing (eSign). Its RESTful gateway API lets companies create identification orders, drive the verification flow, retrieve results and documents, and subscribe to status webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/idnow/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/idnow/refs/heads/main/apis.yml)

## Tags

- Identity Verification
- KYC
- Identity Proofing
- AML
- eSign

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### IDnow Identifications API

Create and drive identification orders for a company. Endpoints create an identification for a transaction, start it, and request the video chat step, authenticated with the company login token obtained from the gateway login.

- **Human URL:** [https://docs-videoident.idnow.io/](https://docs-videoident.idnow.io/)
- **Base URL:** `https://gateway.idnow.de/api/v1`

#### Tags

- Identifications
- KYC
- Onboarding

#### Properties

- [Documentation](https://docs-videoident.idnow.io/)
- [OpenAPI](openapi/idnow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/idnow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/idnow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IDnow Results & Retrieval API

Retrieve the result of a completed identification as JSON and download the captured documents and evidence, optionally including the ID-document and face images once the identification has finished.

- **Human URL:** [https://docs-videoident.idnow.io/](https://docs-videoident.idnow.io/)
- **Base URL:** `https://gateway.idnow.de/api/v1`

#### Tags

- Results
- Retrieval
- Documents

#### Properties

- [Documentation](https://docs-videoident.idnow.io/)
- [OpenAPI](openapi/idnow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/idnow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/idnow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IDnow AutoIdent API

Fully automated digital identity verification that establishes ownership and authenticity of a user's ID document and matches it against a live selfie, created and retrieved through the same gateway identification resources.

- **Human URL:** [https://docs-autoident.idnow.io/](https://docs-autoident.idnow.io/)
- **Base URL:** `https://gateway.idnow.de/api/v1`

#### Tags

- AutoIdent
- Automated KYC
- Document Verification

#### Properties

- [Documentation](https://docs-autoident.idnow.io/)
- [OpenAPI](openapi/idnow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/idnow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/idnow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IDnow VideoIdent API

Human-assisted identity verification where a user presents a supported ID document over video chat guided by an IDnow Ident Specialist, including a request to enter the video-chat queue for the identification.

- **Human URL:** [https://docs-videoident.idnow.io/](https://docs-videoident.idnow.io/)
- **Base URL:** `https://gateway.idnow.de/api/v1`

#### Tags

- VideoIdent
- Video KYC
- Ident Specialist

#### Properties

- [Documentation](https://docs-videoident.idnow.io/)
- [OpenAPI](openapi/idnow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/idnow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/idnow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IDnow Webhooks

Status-change notifications delivered to a subscriber URL when an identification changes state. Webhooks are delivered by GET by default and support a [statusCode] placeholder in the configured callback URL.

- **Human URL:** [https://docs-videoident.idnow.io/](https://docs-videoident.idnow.io/)
- **Base URL:** `https://gateway.idnow.de/api/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs-videoident.idnow.io/)
- [OpenAPI](openapi/idnow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/idnow)
- [LinkedIn](https://www.linkedin.com/company/idnow)
- [Website](https://www.idnow.io)
- [Documentation](https://www.idnow.io/developers/)
- [Plans](plans/idnow-plans-pricing.yml)
- [Rate Limits](rate-limits/idnow-rate-limits.yml)
- [Fin Ops](finops/idnow-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
