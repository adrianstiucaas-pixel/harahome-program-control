# Major Program Decisions

Updated: 2026-08-20

1. Use `DISCOVER → REUSE → CONNECT → COMPLETE GAPS`.
2. Business logic remains canonical; parallel engines are not introduced when a canonical owner already exists.
3. Real ANAF operations remain fail-closed until separately authorized.
4. External writes are controlled and require explicit authority.
5. EF-7 precedes Human UX work.
6. The sequence after EF-7 is Human Information Architecture → Professional Visual Cleanup → EF-8 Ask HaraHome.
7. Finclub uses the `SUPPLIER_FULFILLED` model.
8. Bucharest is modeled as an external fulfillment and return node.
9. Dropshipping NIR is accounting-only and must not fabricate physical HaraHome stock.
10. A monthly dropshipping statement is required.
11. The target AWB notification direction is email to the warehouse, not a manual WhatsApp workflow.
12. WooCommerce is the only active live-read sales channel in this stage; every WooCommerce write remains disabled.
13. eMAG BG is intentionally inactive, while eMAG RO and Trendyol remain pending live activation; eMAG HU is preserved.
14. Invoice testing cannot start until an isolated UAT numbering capability exists.
