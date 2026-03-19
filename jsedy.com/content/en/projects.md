---
title: "Projects"
---

## XINEX progress

_Last update: 2026-03-19 CET_

{{< progressbar label="Project readiness" value="85" note="Complete flat-surface UI refresh (v0.44) — visual language unified with loading screen DNA. Critical login and session cookie bugs fixed. Batch planning system created. <strong>Next:</strong> Security batches (SSRF, TLS, deployment hardening)." >}}

{{< progressbar label="User readiness" value="77" note="Login now works reliably (datetime serialization fix + Secure cookie flag fix). UI significantly cleaned up: flat surfaces, compact monitor rows, status-first inventory, outage banner, collapsible incidents." >}}
{{< progressbar label="Administration" value="76" note="System Console covers provider-event simulation, webhook-backed billing ingestion, and richer Product Web locale editing." >}}
{{< progressbar label="Product web" value="59" note="Product Web now supports hero/highlights copy editing and pricing card add/remove/reorder in admin." >}}
{{< progressbar label="Security" value="53" note="Session cookie flags fixed (Secure, HttpOnly, SameSite). Webhook signature verification added; SSRF, ReDoS and TLS hardening are next (batches 01-03)." >}}
{{< progressbar label="Automation & delivery" value="46" note="Local workflows stable; cloud deployment automation remains in progress." >}}

### Next milestone

- Security batch 01: SSRF + ReDoS fixes
- Security batch 02: TLS, SSH, secrets hardening
- Security batch 03: Deployment fixes + security headers
