# HaraHome Program Control Rules

This repository is PUBLIC and is used only for sanitized program coordination between the Owner, ChatGPT, and Codex.

## Public repository safety

NEVER publish:

- secrets, tokens, or passwords;
- Client Secrets or OAuth tokens;
- certificate private keys;
- `.env` files;
- databases, WAL, or SHM files;
- customer data;
- real invoices;
- customer addresses, telephone numbers, or email addresses;
- unsanitized logs.

Publish only sanitized technical information.

This repository is not the source repository for HaraHome. Product source code and the product workspace remain separate.

## End-of-task protocol

At the end of every authorized HaraHome task:

1. Update `docs/program/PROGRAM_STATE.md`.
2. Update `docs/program/CURRENT_BASELINE.md` only if the accepted live release changed.
3. Save a sanitized report in `reports/`.
4. Record the exact verdict.
5. Include version, schema, tests, UAT, and SHA when they exist.
6. Record real blockers.
7. Do not start the next stage automatically.
