# snykchallenge

A small archive of two challenge-completion receipt records. This repository contains no application or runnable security exercise.

## Contents

- `completion.json` and `proof.json` preserve the receipt fields and completion IDs.
- Their `completionToken` values are explicit removed-value markers, not usable credentials or verified proof of completion.

The original JWT-format strings declared expiry dates of October 8, 2026 at 23:00 UTC. Their signatures, issuer and server-side expiry enforcement have not been verified. Original strings may remain in Git history; replacing a value does not revoke it at its issuer.

## Handling new receipts

Keep raw receipts and environment secrets local. The ignored `.completion-local/` directory is available for that purpose; inspect staged files before committing. Do not publish new tokens or resubmit historical receipts as a security test.

The challenge's issuing service and original exercise are not documented here. This archive does not establish the purpose or safety of any separate exercise. No project license has been selected.
