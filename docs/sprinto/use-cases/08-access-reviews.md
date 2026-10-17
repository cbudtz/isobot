# UC-08 — Access reviews and critical systems

## Situation

Periodic user access reviews across critical systems are required; accounts must map to staff, access must be justified, and leavers must be deprovisioned.

## Actors

- System owners (delegated ownership per critical system)
- IT / security reviewers
- Managers approving access

## Trigger

Quarterly/annual review cadence, offboarding events, failed access monitors.

## Flow

1. **Register systems** — Add critical systems (via integrations: AWS, GCP, Okta, Entra ID, GitHub, Confluence, Cloudflare, DocuSign, Asana, Freshservice, …) or manually; group into access registers.
2. **Map users** — Link accounts to staff records; classify non-staff/service accounts; resolve unidentified users.
3. **Define rules** — Role-based access validation; ticket-based access validation (MCAS) using Jira/ServiceNow-style tickets.
4. **Review** — Perform access review per system; create remediation tasks for findings; mark tasks complete.
5. **Offboarding** — Review offboarded staff access and confirm revocation.
6. **Monitor** — Authentication & access monitors (MFA, login protection, inactive users).

## Sprinto capabilities used

System Access module · access registers · ticket-based validation · Okta / IAM integrations · access monitors · remediation tasks.

## Outcome

Evidence-backed, repeatable access reviews with clear ownership; reduced orphaned accounts.

## Related

[UC-06](./06-people-compliance.md), [UC-09](./09-change-and-vulnerability-management.md).
