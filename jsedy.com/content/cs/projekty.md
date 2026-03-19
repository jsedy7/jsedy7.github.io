---
title: "Projekty"
---

## Progress XINEX projektu

_Poslední aktualizace: 2026-03-19 (sprint 23+24+13+21+32+37)_

{{< progressbar label="Připravenost projektu" value="99" note="v0.50.0-alpha – všechny batche 01–42 dokonceny (krome LATER/FAR FUTURE). Sprint: infra hardening (23), pytest CI (24), onboarding tipy (13), accessibility (21), ping probe multi-thread (32), product web redesign (37). Migrace 028." >}}

{{< progressbar label="Uživatelská připravenost" value="93" note="Welcome tipy po prvnim monitoru. Ping monitor detail bez HTTP/SSL sekcí. Skip-link přístupnost. Prázdné stavy pro notifikace. Quick wizard, first-run hint, onboarding wizard." >}}
{{< progressbar label="Administrace" value="95" note="Integrations feature gate, site statistics, account suspenze + impersonace. IP blocklist. Probers management. Audit log s filtry + detailem." >}}
{{< progressbar label="Produktový web" value="95" note="Velký redesign dokoncen: sekce Jak to funguje (3 kroky), Diagnostic depth (6 karet), Trust bar. Hero, highlights, pricing, comparison. Responsive CSS." >}}
{{< progressbar label="Security" value="93" note="SSRF, ReDoS, headers. Rate limiting (nginx + app). IP blocklist middleware. Per-email lockout. Account suspension. CI security audit (pip-audit)." >}}
{{< progressbar label="Automatizace a nasazení" value="88" note="pytest unit testy (auth, monitors, incidents), CI pipeline (lint+test+tsc+pip-audit), k6 load test, backup-db.sh, Docker health checks, alert rules rozšíreny." >}}

---

### Nejbližší milestone

**Sprint dokoncen (23, 24, 13, 21, 32, 37):**
- Batch 23 – Infra hardening: DB pool, /health DB ping, data retention, Docker health checks, backup-db.sh, nginx gzip, alert rules
- Batch 24 – Testing: pytest unit testy, CI pipeline (GitHub Actions), k6 load test
- Batch 13 – Onboarding: welcome tipy po prvnim monitoru (auto-dismiss)
- Batch 21 – Accessibility: skip-link, focus CSS, empty states pro notifikace
- Batch 32 – Ping probe: ThreadPoolExecutor, ping monitor detail UI
- Batch 37 – Product web: sekce Jak to funguje + Diagnostic depth + Trust bar

**Zbývá pro beta launch:**
- Batch 04 – AWS první nasazení (manuální kroky: IAM, SES, terraform apply, DNS, TLS)
