---
title: "Projekty"
---

## Progress XINEX projektu

_Poslední aktualizace: 2026-03-18 23:15 CET_

{{< progressbar label="Připravenost projektu" value="82" note="Základ produktu běží lokálně, nově i se signed Stripe webhook ingestí, billing-event deduplikací a Product Web copy editací (hero + highlights + pricing row controls). <strong>Další krok:</strong> hardening mapování webhook eventů + Product Web constants preview/diff." >}}

{{< progressbar label="Uživatelská připravenost" value="72" note="Core monitoring UX existuje; tenant pravidla teď zahrnují lifecycle-aware billing sync a bezpečnější přechody subscription stavů." >}}
{{< progressbar label="Administrace" value="76" note="System Console už umí provider-event simulaci i webhook-backed billing ingest a bohatší Product Web locale editaci." >}}
{{< progressbar label="Produktový web" value="59" note="Produktový web teď podporuje editaci hero/highlights copy a pricing card add/remove/reorder v administraci." >}}
{{< progressbar label="Security" value="51" note="Přibyla verifikace webhook signatury a replay-safe ingest; 2FA/hardening zůstává v roadmapě." >}}
{{< progressbar label="Automatizace a nasazení" value="46" note="Lokální workflow stabilní, cloud automatizace je stále rozpracovaná." >}}

### Nejbližší milestone

- Hardening mapování Stripe webhook eventů + Product Web constants preview/diff.
