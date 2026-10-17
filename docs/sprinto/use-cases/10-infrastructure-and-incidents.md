# UC-10 — Cloud infrastructure and incident monitoring

## Situation

Cloud resources must meet configuration baselines (encryption, backups, logging, alarms) and incidents must be tracked to closure, with evidence for availability and security criteria.

## Actors

- Infra / platform engineers (infra owners)
- On-call / SRE
- Security lead

## Trigger

New cloud accounts or services, failed infra checks, incidents, DR planning, audit periods.

## Flow

### Infrastructure
1. Connect AWS (IAM role; 70+ checks; tag-based monitor activation), Azure, GCP (Workload Identity Federation), DigitalOcean, Cloudflare, Datadog, others.
2. Classify entities as Production / Not Production; assign infra owners.
3. Monitors evaluate configuration; failing checks become tasks; Sprinto Assist or Fix-It agent may remediate (e.g. CloudWatch alarms).
4. Non-integrating providers tracked via workflow checks and evidence.
5. Asset Register unifies infra, devices, repos, people and systems; link assets to risks.

### Incidents
1. Add incident sources (PagerDuty, Microsoft Defender, Freshservice, Incident.io, Zenduty, email).
2. Incident checks ensure reported incidents are closed and data-loss reporting handled.
3. Report and resolve incidents in Sprinto when no external tool exists.

## Sprinto capabilities used

Infrastructure module · Incidents module · Asset Register · cloud monitors · infra owners · workflow checks · remediation agents.

## Outcome

Continuous cloud baseline evidence and incident traceability; prioritized remediation by production relevance.

## Related

[UC-07](./07-device-compliance.md), [UC-09](./09-change-and-vulnerability-management.md), [UC-13](./13-enterprise-risk-management.md).
