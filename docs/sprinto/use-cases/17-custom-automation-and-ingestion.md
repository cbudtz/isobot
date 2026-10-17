# UC-17 — Custom automation, ingestion and API

## Situation

Internal tools, niche SaaS or bespoke infrastructure must feed compliance monitoring, and compliance operations must integrate with the company's own tooling.

## Actors

- Platform / DevOps engineers
- GRC engineers
- Internal tool owners

## Trigger

Unsupported system in scope, need for real-time evidence, desire to automate repetitive GRC tasks, AI-assistant integration.

## Flow

1. **Ingestion plans** — Define entity types; build plans (providers, credentials, steps) with templates, YAML or AI editor; scheduled sync or webhooks; run/debug history; records trigger checks.
2. **Developer API (GraphQL)** — Scope staff, upload evidence, push pentest reports, read framework health and vendor data; API Playground and cookbooks; custom integration push APIs.
3. **Programmable monitors** — Rule builder evaluates custom conditions on integrated or native entities; custom API checks (Growth).
4. **Automations** — Rule engine triggers tasks, notifications and workflows on events; configurable SLAs; approval paths.
5. **Ticketing** — Jira Active Sync (two-way) and other ticketing systems for tasks.
6. **Sprinto MCP** — Expose Sprinto to AI assistants via Model Context Protocol.

## Sprinto capabilities used

Ingestion module · Developer API · custom integrations · programmable monitors · Automations · Jira Active Sync · Sprinto MCP · custom fields.

## Outcome

Bespoke systems covered by the same control and evidence model; GRC workflows embedded in engineering tooling.

## Related

[UC-09](./09-change-and-vulnerability-management.md), [UC-16](./16-custom-obligations.md), [UC-18](./18-ai-assisted-operations.md).
