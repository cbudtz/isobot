# UC-06 — People compliance: onboarding, offboarding, training

## Situation

Frameworks require evidence that staff are scoped, background-checked where applicable, trained, onboarded with security steps and offboarded with access removal.

## Actors

- HR / People Ops
- IT / security
- Managers and staff
- Auditors

## Trigger

Joiner, mover or leaver events; periodic training cycle; audit evidence requests.

## Flow

1. **Sync staff** — Import from HRIS/IdP (BambooHR, Deel, ADP, Workday, Google Workspace groups, …); auto-group employees; org charts.
2. **Scope** — Smart scoping rules decide in-scope vs not-in-scope staff; API can set scope programmatically.
3. **Onboard** — Assign policies, training and onboarding actions; BGV reports via Checkr/Certn or upload.
4. **Train** — Launch campaigns with built-in modules or KnowBe4 / Curricula / Workday LMS; group-specific and custom modules (Growth).
5. **Offboard** — Offboarding workflow triggers access revocation checklist and review of offboarded staff access.
6. **Monitor** — People monitors (training completion, acknowledgement, BGV, offboarding) feed controls and evidence.

## Sprinto capabilities used

People module · Trainings · security roles · Employee Portal · HRIS and IdP integrations · background verification integrations · People Ops automation.

## Outcome

Joiner/mover/leaver evidence tied to controls automatically; fewer gaps at audit for training and access removal.

## Related

[UC-05](./05-policy-management.md), [UC-07](./07-device-compliance.md), [UC-08](./08-access-reviews.md).
