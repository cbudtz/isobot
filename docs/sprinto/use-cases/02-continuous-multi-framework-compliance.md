# UC-02 — Continuous multi-framework compliance

## Situation

The organization has passed one audit and now carries several overlapping frameworks (e.g. SOC 2 + ISO 27001 + HIPAA + PCI DSS) with recurring audit periods. Sprinto frames this as "trust ops on autopilot" versus a "recurring fire drill".

## Actors

- Security / GRC lead (program owner)
- Control owners across engineering, IT, HR
- Auditors (multiple engagements)

## Trigger

Adding a second framework; Type II observation windows; customer-specific control requirements.

## Flow

1. **Cross-map** — Enable new framework; CCF/SCF reuses existing controls and only surfaces net-new criteria.
2. **Monitor** — Automated monitors run continuously; workflow checks recur on schedule (periodic reviews, risk assessments, access reviews).
3. **Detect drift** — Policy drift detection and failing checks raise tiered, time-bound alerts (Slack/Teams/Jira).
4. **Remediate** — Tasks with SLAs; Sprinto Assist / Fix-It agent / Terraform remediation where enabled; special cases for justified exceptions.
5. **Refresh evidence** — Time-valid evidence pipelines; AI evidence gap analysis validates relevance and timeliness.
6. **Report** — Control health dashboard, compliance health and gap reports, rolling audit packs.

## Sprinto capabilities used

Common Control Framework · frameworks and criteria management · automated and programmable monitors · rule engine and automations · special cases · evidence library and signed artifacts · reports and dashboards.

## Outcome

Always-ready posture across frameworks; one set of controls and evidence serving many audits; reduced duplicate evidence collection.

## Related

[UC-01](./01-first-certification.md), [UC-03](./03-multi-entity-zones.md), [UC-04](./04-audit-management.md), [UC-16](./16-custom-obligations.md), [UC-18](./18-ai-assisted-operations.md).
