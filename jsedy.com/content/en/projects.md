---
title: "Projects"
---

## XINEX progress

_Last update: 2026-03-19 (sprint 23+24+13+21+32+37)_

{{< progressbar label="Project readiness" value="99" note="v0.50.0-alpha — all batches 01–42 completed (except LATER/FAR FUTURE). Sprint: infra hardening (23), pytest CI (24), onboarding tips (13), accessibility (21), ping probe multi-thread (32), product web major redesign (37). Migration 028." >}}

{{< progressbar label="User readiness" value="93" note="Welcome tips after first monitor. Ping monitor detail hides HTTP/SSL sections. Skip-link accessibility. Empty state for notification channels. Onboarding wizard, quick wizard, first-run hint." >}}
{{< progressbar label="Administration" value="95" note="Integrations feature gate, site statistics, account suspension + impersonation. IP blocklist. Probers management. Audit log with filters + detail modal. CI security audit." >}}
{{< progressbar label="Product web" value="95" note="Major redesign complete: How it works (3 steps), Diagnostic depth (6 feature cards), Trust bar. Hero, pricing, comparison table. Responsive CSS." >}}
{{< progressbar label="Security" value="93" note="SSRF, ReDoS, headers. nginx + app rate limiting. IP blocklist middleware. CI pipeline with pip-audit. Per-email lockout. Account suspension." >}}
{{< progressbar label="Automation & delivery" value="88" note="pytest unit tests (auth, monitors, incidents), GitHub Actions CI (lint+test+tsc+security), k6 load test, backup-db.sh with S3, Docker health checks, extended alert rules." >}}

---

### Next milestone

**Sprint completed (23, 24, 13, 21, 32, 37):**
- Batch 23 - Infra hardening: DB pool 5/20, /health DB ping, data retention + cleanup loop, Docker health checks, backup-db.sh, nginx gzip, extended alert rules
- Batch 24 - Testing: pytest unit tests, GitHub Actions CI pipeline, k6 load test
- Batch 13 - Onboarding: welcome tips after first monitor (auto-dismiss, 10s)
- Batch 21 - Accessibility: skip-link, focus CSS, empty state for notification channels
- Batch 32 - Ping probe: ThreadPoolExecutor (PROBE_MAX_WORKERS=20), ping monitor detail UI
- Batch 37 - Product web: How it works + Diagnostic depth + Trust bar sections

**Remaining for beta/AWS launch:**
- Batch 04 - AWS first deployment (manual steps: IAM, SES, terraform apply, DNS, TLS)
