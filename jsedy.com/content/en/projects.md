---
title: "Projects"
---

## XINEX progress

_Last update: 2026-03-19 14:20 CET_

{{< progressbar label="Project readiness" value="97" note="v0.47.0-alpha — batches 01-36, 40 of 42 completed. This sprint: integrations feature gate (34), site statistics (40), account suspension + impersonation (31). Migrations 022-024." >}}

{{< progressbar label="User readiness" value="90" note="Email + Telegram alerts, onboarding wizard, first-run hint. Login page redesign with show/hide password. Heartbeats progress bar. Quick wizard simplified. Impersonation banner when in impersonation mode." >}}
{{< progressbar label="Administration" value="90" note="Integrations feature gate: enable/disable per-integration from System Console (SQL registry + admin UI). Site statistics: KPI cards, check volume, monitor type breakdown. Account suspension + impersonation (audited, max 3 sessions, cannot impersonate admin)." >}}
{{< progressbar label="Product web" value="78" note="Hero, highlights, quickstart docs, production legal texts. Full redesign planned in batch 37." >}}
{{< progressbar label="Security" value="84" note="SSRF, ReDoS, HTTP headers. Per-email lockout. Account suspension (403 on login + API). Impersonation: audited, visible banner, max 3 concurrent sessions, cannot impersonate platform admins." >}}
{{< progressbar label="Automation & delivery" value="57" note="QA checklist, integration docs. pytest unit tests and CI pipeline planned in batch 24." >}}

---

### Next milestone

**Sprint completed (34, 40, 31):**
- Batch 34 - Integrations feature gate (enable/disable from System Console)
- Batch 40 - Site Statistics (KPI cards, checks volume, monitor distribution)
- Batch 31 - Account management: suspension + impersonation (audited, banner in UI)

**Queued:**
- Batch 33 - Probers management in System Console
- Batch 32 - Ping probe architecture
- Batch 37 - Product web major redesign
- Batch 42 - Defensive mechanisms (IP blocklist, abuse detection)
