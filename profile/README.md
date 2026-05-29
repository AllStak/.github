<h1 align="center">AllStak</h1>

<p align="center">
  <strong>Unified observability platform.</strong><br/>
  Errors · logs · distributed tracing · infrastructure metrics · uptime · alerting.<br/>
  One sign-in, one tenant model, one correlated dataset across every signal.
</p>

<p align="center">
  <a href="https://allstak.sa">Website</a> ·
  <a href="https://docs.allstak.sa">Documentation</a> ·
  <a href="https://changelog.allstak.sa">Changelog</a> ·
  <a href="https://allstak.sa/en/security">Security</a> ·
  <a href="https://allstak.sa/en/status">Status</a>
</p>

---

## Platform

| Surface | Status |
|---|---|
| Error tracking — fingerprinting, regressions, spike detection | Production |
| Logs — high-cardinality, full-text searchable | Production |
| Distributed tracing — OpenTelemetry-compatible, span-level drilldown | Production |
| HTTP request analytics — p95, status distribution, top endpoints | Production |
| Infrastructure metrics — host, container, service-level signals | Production |
| Uptime & cron monitors — synthetic checks with on-call routing | Production |
| Performance & Apdex — page-, route-, query-level | Production |
| Database query monitoring — slow-query insight, trend tracking | Production |
| Incidents — timeline, trace correlation, ack/resolve workflow | Production |
| Unified alerting — Slack, Jira, GitHub, Teams, PagerDuty, Opsgenie, Telegram, webhooks | Production |
| MCP — Model Context Protocol surface for AI agents | Production |

## SDKs

Per-language SDKs are maintained in dedicated repositories under this org.
Each ships session tracking, offline event buffering, automatic PII
sanitization at the SDK boundary, and a shared trace-propagation wire
format so traces stitch across languages.

JavaScript / TypeScript (browser, Node, Next.js, React Native) · Python ·
Go · Ruby · Java / Spring Boot · .NET · PHP · Rust · Elixir · Swift / iOS ·
Kotlin / Android · Flutter.

## Engineering principles

- **Honest surfaces.** Empty states say "no data yet." We don't claim
  certifications we don't hold.
- **Privacy at ingest.** The ingest pipeline strips likely secrets before
  events reach storage. Strict-mode organizations drop city/region geo
  at the ingest boundary.
- **Tenant isolation as a hard rule.** Every authorized request is scoped
  through `organization_members`; cross-tenant access is rejected at the
  controller layer, not patched at the query layer.
- **First-class Arabic & RTL.** Across dashboard, mobile, marketing, and
  SDKs. Billing in SAR with international card support.

## Get in touch

- Sales · support · security · partnerships · press → [hello@allstak.sa](mailto:hello@allstak.sa)
- X / Twitter → [@AllStak](https://x.com/AllStak)
- LinkedIn → [linkedin.com/company/allstak](https://www.linkedin.com/company/allstak)

Security disclosures are acknowledged within one business day. See
<https://allstak.sa/en/security> for our responsible-disclosure terms.

---

<p align="center">
  <a href="https://www.saudimade.sa">
    <img src="./saudi-made.png" alt="Saudi Made" width="220" />
  </a>
</p>

<p align="center">
  <sub>© AllStak · Riyadh, Kingdom of Saudi Arabia</sub>
</p>
