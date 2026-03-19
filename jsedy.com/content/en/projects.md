---
title: "Projects"
---

## XINEX progress

_Last update: 2026-03-22 CET_

{{< progressbar label="Project readiness" value="88" note="v0.46.0-alpha — SSRF protection in API, probe-local, and probe-lambda. ReDoS timeout wrapper for body-regex. Startup secret validation refuses insecure defaults. HTTP security headers (Next.js + nginx). Terraform SSH CIDR restriction, IMDSv2 enforcement, SES IAM scoped to identity. Migration script applies all SQL files in sorted order. Onboarding empty-state with single-URL wizard." >}}

{{< progressbar label="User readiness" value="81" note="Onboarding wizard for new users (empty state → URL → start monitoring in 30s). Monitor detail shell with trial badge, sign out, and extended nav. Organisation name required at registration." >}}
{{< progressbar label="Administration" value="76" note="System Console covers provider-event simulation, webhook-backed billing ingestion, and richer Product Web locale editing." >}}
{{< progressbar label="Product web" value="59" note="Product Web now supports hero/highlights copy editing and pricing card add/remove/reorder in admin." >}}
{{< progressbar label="Security" value="71" note="SSRF blocking of private/reserved IPs in API and both probes. ReDoS protection via thread with 2s timeout. Startup secret validation. HTTP security headers (CSP, Permissions-Policy). Terraform SSH CIDR, IMDSv2, SES IAM scoped." >}}
{{< progressbar label="Automation & delivery" value="52" note="Migration deployment fixed (all *.sql files applied in sorted order). Local workflows stable; cloud deployment in progress." >}}

### Next milestone

- Batch 04: AWS deploy (cloud automation)
- Batch 05: Onboarding wizard expansion
- Batch 13: Registration + onboarding flow completion
