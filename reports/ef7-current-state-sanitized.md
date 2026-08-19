# EF-7 — Sanitized Current State

Date: 2026-08-19

## Inventory Truth R1

`HARAHOME_ENTERPRISE_EF7_INVENTORY_TRUTH_R1 = PASS`

- Historical accepted release: `2.12.0-enterprise-ef7-inventory-truth-r1`
- Schema: `23013`
- Product identity and physical stock movement ownership: canonical
- Physical, reserved, and available stock: explicitly separated
- EF-7 targeted tests: `32/32 PASS`
- Combined UAT: `12/12 PASS`
- Live HTTP validation at cutover: `14/14 PASS`
- Database integrity: `ok`
- Foreign-key violations: `0`
- Marketplace stock writes and other new external writes: `0/OFF`
- Package SHA-256: `e94261b860e887eeb0436a11069e88cd7b9bd0350836088f74111b39dddc61b7`

The release was accepted and later superseded without changing schema `23013`.

## Finclub Supplier Fulfillment & Accounting R1

- Technical candidate verdict: `PASS_LOCAL_TECHNICAL`
- Operational activation: `BLOCKED_FOR_OPERATIONAL_ACTIVATION`
- Production deployment: `NOT AUTHORIZED`
- Candidate schema: `23014`; not applied to live
- Targeted tests: `46/46 PASS`
- Executable regressions: `153/153 PASS`
- Combined UAT: `50/50 PASS`
- Real warehouse email, courier write, supplier write, marketplace write, and ANAF write: `0`
- Candidate package SHA-256: `48cd4a53cbaba6bdc052b9bbecb222acc0de18b75d62767bcc730539a80f2fae`

Real supplier identity/configuration, courier references, and separate deployment authority remain required. No private supplier or contact details are included in this public report.
