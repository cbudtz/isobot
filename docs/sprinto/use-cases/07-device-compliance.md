# UC-07 — Endpoint and device compliance

## Situation

Laptops and phones used by in-scope staff must demonstrate encryption, screen lock, antivirus and OS patching for SOC 2 / ISO 27001 / HIPAA.

## Actors

- IT administrators
- Staff (self-reporting when no MDM)
- Security lead

## Trigger

Program setup, new devices, failed device checks, audit evidence period.

## Flow

1. **Choose reporting mode** — Dr. Sprinto agent (macOS/Windows/Linux), third-party MDM (Intune, Jamf, Kandji, JumpCloud, Hexnode, ManageEngine, ScaleFusion, Chromebook), or manual workflow checks.
2. **Inventory** — Devices discovered or imported; ownership mapped to staff; scope as Active / Inactive / Not-in-Scope.
3. **Check** — Encryption, auto screen lock, antivirus, OS version; extended checks through MDM integrations; EDR data via CrowdStrike.
4. **Remediate** — Staff receive tasks via Employee Portal; manual device status upload if scanning unsupported.
5. **Evidence** — Device status and check history become audit evidence.

## Sprinto capabilities used

Staff Devices module · Dr. Sprinto · MDM/EDR integrations · manual workflow checks · Employee Portal · device monitors.

## Outcome

Continuous device posture evidence without a separate MDM purchase for small teams; MDM-backed depth for larger ones.

## Related

[UC-06](./06-people-compliance.md), [UC-10](./10-infrastructure-and-incidents.md).
