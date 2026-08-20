# HaraHome Program State

Updated: 2026-08-20

This document contains sanitized coordination data only.

## Stage status

- EF-7 = PASS
- MENU CONSOLIDATION = PASS
- PROFESSIONAL UX = PASS
- OPERATIONAL TRUTH R1 = PASS
- WOOCOMMERCE LIVE READ SYNC R1 = PASS

Finclub supplier fulfillment is now integrated into the accepted baseline with explicit owner review for NIR. Real supplier/courier configuration and every external write remain off pending separate owner action or authorization.

## Live baseline

- LIVE VERSION: `2.15.2-enterprise-woocommerce-sync-action-hotfix-r1`
- LIVE SCHEMA: `23016`
- LIVE PORT: `8765`
- LIVE PID: `14216` (listener confirmed on 2026-08-20; operational PIDs may change after a controlled restart)
- DB INTEGRITY: `integrity_check=ok`
- FK STATUS: `0` violations
- SALES CHANNELS: WooCommerce `ACTIVE/CURRENT`; eMAG BG `INACTIVE`; eMAG RO and Trendyol `PENDING`; eMAG HU preserved

## Program control

- CURRENT TASK: WooCommerce Real Test Order — Ingestion & Order360 Validation R1 — `IN_PROGRESS`
- LAST COMPLETED TASK: WooCommerce Sync Action Hotfix R1
- NEXT: Owner test order validation only after explicit authorization
- EF-8 Ask HaraHome 2.0: `NOT STARTED` and not authorized as a current task

No subsequent product stage may start without an authorized task.
