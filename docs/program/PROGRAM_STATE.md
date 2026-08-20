# HaraHome Program State

Updated: 2026-08-20

This document contains sanitized coordination data only.

## Stage status

- EF-7 = PASS
- MENU CONSOLIDATION = PASS
- PROFESSIONAL UX = PASS
- OPERATIONAL TRUTH R1 = PASS

Finclub supplier fulfillment is now integrated into the accepted baseline with explicit owner review for NIR. Real supplier/courier configuration and every external write remain off pending separate owner action or authorization.

## Live baseline

- LIVE VERSION: `2.15.0-enterprise-end-to-end-operational-truth-r1`
- LIVE SCHEMA: `23015`
- LIVE PORT: `8765`
- LIVE PID: `10076` (listener confirmed on 2026-08-20; operational PIDs may change after a controlled restart)
- DB INTEGRITY: `integrity_check=ok` in the last accepted cutover report
- FK STATUS: `0` violations in the last accepted cutover report
- DATA FRESHNESS: truthful live status is exposed; current remaining states are `STALE 1`, `ERROR 3`, `DISCONNECTED 1`, and `NOT_CONFIGURED 12`

## Program control

- CURRENT TASK: Sales / Orders — WooCommerce Live Read Sync R1 — `IN_PROGRESS`
- LAST COMPLETED TASK: End-to-End Business Orchestration, Operational Truth, Live Data Freshness & System-Wide Consolidation R1
- NEXT: determine only from the real configuration and freshness gaps recorded in the final report
- EF-8 Ask HaraHome 2.0: `NOT STARTED` and not authorized as a current task

No subsequent product stage may start without an authorized task.
