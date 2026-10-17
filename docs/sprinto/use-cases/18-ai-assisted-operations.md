# UC-18 — AI-assisted operations (Sprinto AI, Sprinto Assist)

## Situation

A small team must operate a large GRC surface; repetitive work (mapping, evidence validation, remediation, questionnaires, vendor reviews) consumes capacity.

## Actors

- GRC / security operators
- Engineers remediating failing monitors
- Sales / customer-facing teams

## Trigger

Failing monitors, evidence review before audit, incoming questionnaires, vendor documents, new integrations to connect.

## Flow

1. **AI Playground & AI Actions** — Create custom AI actions or use Sprinto-defined actions on supported entity types; invoke via Ask AI inside entity records.
2. **Sprinto Assist** — Fix failing monitors directly in AWS and other systems with guided remediation; Integration Agent connects supported integrations from the browser; answer security questionnaires on any portal with evidence attached.
3. **AI mapping** — Suggest policy-to-control and test-to-control mappings; AI-assisted policy drafting.
4. **Evidence gap analysis** — Validate uploaded evidence for relevance, scope and timeliness before audit.
5. **Vendor and AI due diligence AI** — Evaluate SOC 2 reports and security documents.
6. **Autonomous remediation** — Fix-It agent and Terraform-based remediation for misconfigurations (opt-in, approval-gated).

## Sprinto capabilities used

Sprinto AI · AI Playground · Ask AI · Sprinto Assist · Security Questionnaire AI · Vendor Due Diligence AI · evidence gap analysis · Fix-It agent · Sprinto MCP.

## Outcome

Humans approve decisions while the platform executes routine compliance work; faster remediation and audit prep.

## Related

[UC-02](./02-continuous-multi-framework-compliance.md), [UC-11](./11-trust-center-and-questionnaires.md), [UC-12](./12-vendor-risk-management.md), [UC-17](./17-custom-automation-and-ingestion.md).
