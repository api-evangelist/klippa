# Klippa (klippa)

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

Klippa is a document AI platform whose flagship product, DocHorizon (rebranded as Doxis AI.dp following the SER acquisition), provides OCR, classification, conversion, verification, fraud detection and anonymization for 50+ document types. Klippa also publishes dedicated APIs for receipts, invoices, IDs/passports and expense management. EU-hosted; GDPR / ISO 27001 certified.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **DocHorizon (Doxis AI.dp)** — `https://custom-ocr.klippa.com/api/v1` — flagship document AI: OCR, classification, extraction, conversion (JSON/XML/PDF/CSV/XLSX/UBL), verification, fraud detection, anonymization.
- **Financial Documents OCR** — `https://api.klippa.com` — receipts, invoices, bank statements.
- **Klippa Identity Verification (KIV)** — `https://api.klippa.com` — ID/passport verification, face match, liveness.

## OpenAPI
Klippa does not publish a downloadable OpenAPI/Swagger document at a stable public anonymous URL as of 2026-05-08; pipeline did not retrieve a spec into `openapi/`.

## Tags
AI, Document AI, IDP, OCR, Verification, GDPR, EU

## Common Properties
- [Website](https://www.klippa.com/) · [Pricing](https://www.klippa.com/en/pricing/) · [GitHub](https://github.com/klippa-app)
- [Plans](plans/klippa-plans-pricing.yml) — directional only (sales-led, no public list pricing)
- [Rate Limits](rate-limits/klippa-rate-limits.yml) — directional (contract-defined)
- [FinOps](finops/klippa-finops.yml) — reconciled, FOCUS-aligned

## Plans (directional)
- **Free Trial / POC** — time-limited evaluation.
- **DocHorizon** — annual contract sized by volume / modules.
- **Financial OCR** / **KIV** — per-document or per-verification, sales-quoted.
- **Enterprise / On-Prem** — dedicated cluster.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
