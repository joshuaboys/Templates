---
system: "[System/Feature name]"
owner: "@name"
data_classification: Public # Public | Internal | Confidential | Highly Confidential
review_date: YYYY-MM-DD
threat_model_method: STRIDE # or LINDDUN, etc.
status: Draft
---

# Security Design Review — [System/Feature]

## Summary

- Scope of this review and intended audience.

## Architecture & Data Flows

- Diagram(s) with trust boundaries.
- Data lifecycle (collect, process, store, transmit, delete).

## Assets & Assumptions

- Critical assets:
- Security assumptions (and how they’re validated):

## Threat Model

- Entry points / trust boundaries:
- Abuse/misuse cases:
- STRIDE analysis (spoofing, tampering, repudiation, information disclosure, denial of service, elevation of privilege).

## Security Requirements

- Authentication & authorisation (who can do what):
- Secrets management:
- Transport & at‑rest encryption:
- Input validation & output encoding:
- Logging & audit trails (PII handling):
- Rate limiting & DOS protections:

## Third‑Party & Supply Chain

- Dependencies / SBOM link:
- Vendor risk assessment result:

## Privacy

- Data minimisation; purpose limitation; retention:
- User consent & rights handling:

## Testing & Verification

- Static/dynamic analysis:
- Dependency scanning:
- Penetration test plan:
- Security test cases:

## Residual Risk & Approvals

- Residual risk rating:
- Sign‑off: @security, @product, @engineering
