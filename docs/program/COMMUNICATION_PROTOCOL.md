# Communication Protocol

## ChatGPT

- Read `docs/program/PROGRAM_STATE.md`.
- Read the latest final report.
- Verify the recorded verdict.
- Formulate the next task.

## Owner

- Approve sensitive decisions.
- Temporarily transmit the authorized task to Codex while ChatGPT GitHub write access is unavailable.

## Codex

- Execute only the authorized task.
- Publish a sanitized result.
- Do not start a new task automatically.

## Status lifecycle

`NO_TASK_ASSIGNED → READY → IN_PROGRESS → PASS | BLOCKED`

Only the Owner/Architect task handoff can move a product task from `NO_TASK_ASSIGNED` to `READY`.
