# IDnow (idnow)

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
