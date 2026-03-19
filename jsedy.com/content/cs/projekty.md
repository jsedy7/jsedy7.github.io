---
title: "Projekty"
---

## Progress XINEX projektu

_Poslední aktualizace: 2026-03-19 14:20 CET_

{{< progressbar label="Připravenost projektu" value="97" note="v0.47.0-alpha – batche 01–36, 40 z 42 dokonceny. Sprint: integrace feature gate (34), site statistics (40), account suspenze + impersonace (31). Migrace 022–024." >}}

{{< progressbar label="Uživatelská připravenost" value="90" note="Email + Telegram alerty, onboarding wizard, first-run hint. Login page redesign. Heartbeats progress bar. Quick wizard zjednodušen. Impersonation banner." >}}
{{< progressbar label="Administrace" value="90" note="Integrations feature gate: zapnout/vypnout per-integraci (SQL registry + admin UI). Site statistics: KPI karty, check volume, monitor type breakdown. Account suspenze + impersonace (auditovane)." >}}
{{< progressbar label="Produktový web" value="78" note="Hero, highlights, quickstart docs, legal texty. Velky redesign planovany v batch 37." >}}
{{< progressbar label="Security" value="84" note="SSRF, ReDoS, headers. Per-email lockout. Account suspension (403 na login i API). Impersonation: auditovany, bannered, max 3 sessions, cannot impersonate admin." >}}
{{< progressbar label="Automatizace a nasazení" value="57" note="QA checklist, integration docs. pytest unit testy a CI pipeline planovane v batch 24." >}}

---

### Nejbližší milestone

**Sprint dokoncen (34, 40, 31):**
- Batch 34 – Integrace feature gate (zapnout/vypnout per-integraci z System Console)
- Batch 40 – Site Statistics (KPI karty, checks volume, monitor distribution)
- Batch 31 – Sprava uctu: suspenze + impersonace (auditovana, banner v UI)

**Dalsi v pori:**
- Batch 33 – Probers management sekce v System Console
- Batch 32 – Ping probe architektura (multi-type, heartbeat)
- Batch 37 – Product web velky redesign
- Batch 42 – Defensive mechanisms (IP blocklist, abuse detection)
