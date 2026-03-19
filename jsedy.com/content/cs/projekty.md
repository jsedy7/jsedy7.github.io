---
title: "Projekty"
---

## Progress XINEX projektu

_Poslední aktualizace: 2026-03-22 CET_

{{< progressbar label="Připravenost projektu" value="88" note="v0.46.0-alpha – SSRF ochrana v API, probes a lambda. ReDoS timeout wrapper. Startup secret validace. HTTP security headers (Next.js + nginx). Terraform SSH/IMDSv2/SES IAM hardeningа. Migration script opravena. Onboarding empty-state wizard pro prvního monitoru za 30s." >}}

{{< progressbar label="Uživatelská připravenost" value="81" note="Onboarding wizard pro nové uživatele (prázdný stav → URL → start monitoring). Monitor detail shell s trial badge, sign out a rozšířenou navigací. Vyžadováno jméno organizace při registraci." >}}
{{< progressbar label="Administrace" value="76" note="System Console pokrývá provider-event simulaci, webhook-backed billing ingest a Product Web locale editaci." >}}
{{< progressbar label="Produktový web" value="59" note="Produktový web podporuje editaci hero/highlights copy a pricing card add/remove/reorder v administraci." >}}
{{< progressbar label="Security" value="71" note="SSRF blokování privátních/rezervovaných IP v API + obou probes. ReDoS ochrana threadem s timeoutem. Startup secret validace. HTTP security headers (CSP, Permissions-Policy). Terraform SSH CIDR, IMDSv2, SES IAM scoped." >}}
{{< progressbar label="Automatizace a nasazení" value="52" note="Migration deployment fix (všechny *.sql soubory řazeny). Lokální workflow stabilní, cloud automatizace v procesu." >}}

### Nejbližší milestone

- Batch 04: AWS deploy (cloud automatizace)
- Batch 05: Onboarding wizard rozšíření
- Batch 13: Registrace + onboarding flow dokončení
