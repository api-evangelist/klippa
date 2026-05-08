# Klippa (klippa)

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
