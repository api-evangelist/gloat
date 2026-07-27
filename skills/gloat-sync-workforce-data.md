---
name: Sync workforce data into Gloat
description: Authenticate, then upsert users, jobs, and candidacies so an external HR/HCM system stays in sync with Gloat.
api: https://developer.gloat.com/reference/
operations: [user-upsert-1, patchusers-1, job-upsert-1, candidacy-upsert-1, get-candidacy-ids-by-status-1, listusers-1]
source: https://developer.gloat.com/docs/using-gloat-apis
generated: '2026-07-19'
method: generated
---

# Sync workforce data into Gloat

Keep Gloat's talent graph in sync with an upstream HR/HCM system by pushing users,
jobs, and candidacies. All requests are tenant-scoped to
`https://{company_slug}.gloat.com/api`.

## 1. Authenticate
Customer APIs use client-credentials. Base64-encode `CLIENT_ID:CLIENT_SECRET` and POST
it as HTTP Basic to `/api/auth/token`; use the returned JWT as `Authorization: Bearer`
for 24 hours (`expires_in: 86400`). Refresh before expiry. (See `authentication/gloat-authentication.yml`.)

## 2. Upsert users
Send users with `user-upsert-1` (single or bulk). Operations are **idempotent by the
external user id** — re-sending the same id updates rather than duplicates. Use
`patchusers-1` to change status or custom fields only. Confirm with `listusers-1`.

## 3. Upsert jobs
Push open roles with `job-upsert-1`. Retrieve current state with `get-job-by-status-1`
before reconciling.

## 4. Upsert candidacies
Create or update applications with `candidacy-upsert-1`. Poll
`get-candidacy-ids-by-status-1` to reconcile which candidacies changed.

## Conventions to follow
- Bulk endpoints return **HTTP 207 Multi-Status** with per-item status (200 ok, 206 partial, 404 not_found) — always inspect per-item results, not just the top-level code.
- HTTPS only; never log the client secret or JWT.
- See `conventions/gloat-conventions.yml` for pagination, versioning (v1/v2 uri-path), and async patterns.
