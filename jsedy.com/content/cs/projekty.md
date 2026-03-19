---
title: "Projekty"
---

## Progress XINEX projektu

_Poslední aktualizace: 2026-03-19 CET_

{{< progressbar label="Připravenost projektu" value="85" note="Kompletní flat-surface UI refresh (v0.44) – vizuální jazyk sjednocen se loading screen DNA. Opraveny kritické chyby přihlášení a session cookie. Batch systém pro plánování práce vytvořen. <strong>Další krok:</strong> Security batche (SSRF, TLS, deployment hardening)." >}}

{{< progressbar label="Uživatelská připravenost" value="77" note="Login funguje spolehlivě (opravena serializace datetime + Secure cookie flag). UI výrazně vyčištěno: flat surfaces, kompaktní monitor řádky, status-first inventory, outage banner, collapsible incidents." >}}
{{< progressbar label="Administrace" value="76" note="System Console pokrývá provider-event simulaci, webhook-backed billing ingest a Product Web locale editaci." >}}
{{< progressbar label="Produktový web" value="59" note="Produktový web podporuje editaci hero/highlights copy a pricing card add/remove/reorder v administraci." >}}
{{< progressbar label="Security" value="53" note="Opraveny session cookie flags (Secure, HttpOnly, SameSite). Přibyla verifikace webhook signatury; SSRF, ReDoS a TLS hardening jsou další v řadě (batch 01-03)." >}}
{{< progressbar label="Automatizace a nasazení" value="46" note="Lokální workflow stabilní, cloud automatizace je stále rozpracovaná." >}}

### Nejbližší milestone

- Security batch 01: SSRF + ReDoS fixe
- Security batch 02: TLS, SSH, secrets hardening
- Security batch 03: Deployment fixes + security headers
