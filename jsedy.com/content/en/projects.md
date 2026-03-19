---
title: "Projects"
---

## XINEX progress

_Last update: 2026-03-19 14:31 CET_

{{< progressbar label="Project readiness" value="99" note="v0.49.0-alpha — sprint 42+33+18+25+20+22 completed. Rate limiting (nginx + app layer), IP blocklist, probers management, dead probe detection, SEO meta tags + sitemap, account delete, API pagination + X-Request-ID. Migrations 025-027." >}}

{{< progressbar label="User readiness" value="93" note="Account delete (Danger Zone + double confirmation). Probe stale warning in dashboard. Consistent error format with request_id. Pagination on monitor list API." >}}
{{< progressbar label="Administration" value="95" note="Probers section: health status badges, 30s auto-refresh, deregister action. IP Blocklist section: CRUD + audit events. Probe heartbeat endpoint (POST /internal/probe-heartbeat)." >}}
{{< progressbar label="Product web" value="84" note="OG/Twitter meta tags, sitemap.xml, robots.txt, placeholder OG image 1200x630." >}}
{{< progressbar label="Security" value="93" note="nginx rate limit zones (auth 10r/m, api 60r/s, DDoS timeouts, limit_conn 20). IP blocklist middleware (in-memory cache 2min refresh). X-Request-ID on all responses. Consistent error format with request_id field." >}}
{{< progressbar label="Automation & delivery" value="57" note="QA checklist, integration docs. pytest unit tests and CI pipeline planned in batch 24." >}}

---

### Next milestone

**Sprint completed (42, 33, 18, 25, 20, 22):**
- Batch 42 - Defensive mechanisms: nginx rate limiting, IP blocklist, DDoS protection
- Batch 33 - Probers management in System Console (health, auto-refresh, deregister)
- Batch 18 - Dead probe detection: heartbeat endpoint + stale warning in UI
- Batch 25 - Account delete (self-service, soft-delete with confirmation)
- Batch 20 - Marketing SEO: OG tags, sitemap, robots.txt
- Batch 22 - API quality: X-Request-ID, consistent errors, pagination

**Queued:**
- Batch 32 - Ping probe architecture (multi-type)
- Batch 37 - Product web major redesign
- Batch 41 - Admin: roles granularity / platform moderator
