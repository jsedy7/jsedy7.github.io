---
title: "Projekty"
---

## Progress XINEX projektu

_Poslední aktualizace: 2026-03-19 19:15 CET_

{{< progressbar label="Připravenost projektu" value="93" note="v0.47.0-alpha – batche 01–17 dokončeny. Analýza platformy z 9 rolí přinesla 22 nových tasků (batche 18–39)." >}}

{{< progressbar label="Uživatelská připravenost" value="87" note="Email + Telegram alerty, onboarding wizard, first-run hint, subscription usage. Opravy UX a accessibility plánovaný v batch 21 a 25." >}}
{{< progressbar label="Administrace" value="82" note="Product web admin, analytics usage. Plánovaná impersonace, account deaktivace, probers sekce (batche 31, 33)." >}}
{{< progressbar label="Produktový web" value="78" note="Hero, highlights, quickstart docs, legal texty. Velký redesign s diagnostickým zaměřením plánovaný v batch 37." >}}
{{< progressbar label="Security" value="74" note="SSRF, ReDoS, headers. Auth rate limiting, lockout a 2FA příprava plánované v batch 19." >}}
{{< progressbar label="Automatizace a nasazení" value="57" note="QA checklist, integration docs. pytest unit testy a CI pipeline plánované v batch 24." >}}

---

### Časový odhad otevřených tasků (batche 18–39)

| # | Oblast | Odhad |
|---|--------|-------|
| 18 | Reliability – dead probe detection | 2–3 dny |
| 19 | Security – auth rate limiting, 2FA prep | 2–3 dny |
| 20 | Marketing – OG tagy, sitemap, analytics | 1–2 dny |
| 21 | Frontend – accessibility, mobile, empty states | 2–3 dny |
| 22 | API – rate limiting, error formát, stránkování | 2–3 dny |
| 23 | Infra – DB index, health checks, záloha | 2–3 dny |
| 24 | Testing – pytest, CI pipeline | 2–3 dny |
| 25 | UX – plain language, non-tech onboarding | 1–2 dny |
| 26 | UI – sidebar konzistence, Inventory Tile fix | 1–2 dny |
| 27 | UI – dashboard pulsing status dot oprava | 0.5 dne |
| 28 | UX – quick wizard zjednodušení | 0.5 dne |
| 29 | UX – subscription metriky do Analytics | 1 den |
| 30 | Admin – audit log filtry + detail modal | 1.5 dne |
| 31 | Admin – deaktivace účtu + impersonace | 3–4 dny |
| 32 | Probe – ping UI + multi-thread architektura | 5–7 dní |
| 33 | Admin – probers management sekce | 2–3 dny |
| 34 | Admin – integrace feature gate | 1–2 dny |
| 35 | Platform – changelog uživatelský vs. technický | 1–1.5 dne |
| 36 | UI – notif. ikony + login page redesign | 1 den |
| 37 | Product web – velký redesign | 5–7 dní |
| 38 | Docs – uživatelská dokumentace | 2–3 dny |
| 39 | Mobile app | týdny |

| 40 | Site Statistics (KPI, grafy) | 2–3 dny |
| 41 | Permissions – moderátor role | 3–4 dny |
| 42 | Defensive – rate limit mgmt, IP blocklist, API token revoke | 4–6 dní |

**Celkový odhad (bez 38, 39, 41 LATER):** ~47–67 pracovních dní

### Nejbližší milestone

- Opravy vizuálních regresí: **Batch 26** (sidebar) + **Batch 27** (dashboard status pulsing dot)
- Bezpečnostní hardening: **Batch 19** (auth rate limiting, lockout) + **Batch 42** (IP blocklist, abuse detection)
- Infrastruktura: **Batch 18** (dead probe detection) + **Batch 23** (DB index, záloha)

