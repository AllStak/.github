<h1 align="center">AllStak</h1>

<p align="center">
  <strong>Unified observability for modern infrastructure.</strong><br/>
  Errors, logs, distributed traces, infrastructure metrics, uptime, and alerting — in one platform.
</p>

<p align="center">
  <a href="https://allstak.sa">Website</a> ·
  <a href="https://docs.allstak.sa">Docs</a> ·
  <a href="https://changelog.allstak.sa">Changelog</a> ·
  <a href="https://allstak.sa/en/security">Security</a> ·
  <a href="https://allstak.sa/en/status">Status</a>
</p>

---

## What we build

AllStak is a Saudi-built, KSA-hosted observability platform. One sign-in,
one tenant model, one bill. The same query that finds an error opens the
related trace, the related logs, and the host that served the request —
without copy-pasting IDs across five dashboards.

What's live in production today:

- **Error tracking** — fingerprinting, regressions, spike detection
- **Logs** — high-cardinality, full-text searchable
- **Distributed tracing** — OpenTelemetry-compatible, with span-level drilldown
- **HTTP request analytics** — request-level p95, status distribution, top endpoints
- **Infrastructure metrics** — host, container, and service-level signals
- **Uptime monitors + cron monitors** — synthetic checks with on-call routing
- **Performance + Apdex** — page-level, route-level, query-level
- **Database query monitoring** — slow-query insight and trend tracking
- **Incidents** — timeline, trace correlation, acknowledge/resolve workflow
- **Alerting** — a single rule definition that fans out to Slack, Jira, GitHub,
  Discord, Microsoft Teams, PagerDuty, Opsgenie, Telegram, or any webhook
- **MCP access** — first-class Model Context Protocol surface for AI agents

## SDKs

Per-language SDKs ship from their own repositories under this org. Each
covers session tracking, offline event buffering, automatic PII sanitization
at the SDK boundary, and a shared trace-propagation wire format so traces
stitch across languages.

Current languages: JavaScript / TypeScript (browser + Node + Next.js +
React Native), Python, Go, Ruby, Java / Spring Boot, .NET, PHP, Rust,
Elixir, Swift / iOS, Kotlin / Android, Flutter.

Setup typically takes a few minutes — install the SDK, set your project
API key as an environment variable, and call `AllStak.init()`.

## How we work

- **Honesty over polish.** Empty states say "no data yet," not fake charts.
  We don't claim SOC 2 until we hold it.
- **Privacy by default.** The ingest pipeline strips likely secrets before
  they hit storage. Strict-mode orgs drop city/region geo at ingest.
- **Tenant isolation is hard rule.** Every authorized request goes through
  `organization_members`; cross-tenant access is blocked at the controller
  layer, not patched later.
- **Local first, global ready.** First-class Arabic and RTL across the
  dashboard, mobile, and marketing surfaces. Billing in SAR.

## Get in touch

- Sales, support, security, partnerships, press → <a href="mailto:hello@allstak.sa">hello@allstak.sa</a>
- Twitter / X → [@AllStak](https://x.com/AllStak)
- LinkedIn → [linkedin.com/company/allstak](https://www.linkedin.com/company/allstak)
- Security disclosures → email above; we acknowledge within one business day

---

<p align="center">
  <sub>© AllStak · Riyadh, Kingdom of Saudi Arabia</sub>
</p>
