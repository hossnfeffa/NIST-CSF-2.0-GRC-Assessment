# Risk Acceptance and Control Validation

## RA-2026-001 — Risk acceptance request
The IT Director proposed accepting privileged access risk instead of immediate remediation. Acceptance was **not approved**. The fictional risk policy requires validation of exposure, contractual requirements, risk appetite, approval authority and review period; CEO approval is required for high risk, and critical risks exceed normal appetite.

## ESC-2026-001 — Urgent escalation
ADMIN-023 (legacy service account allowing interactive login) and ADMIN-024 (enabled former contractor account) both held privileged RMM access without MFA. Security and system owners were asked to perform authorized containment and investigate logs. **No confirmed incident or compromise** was established.

## VAL-2026-001 — Remediation validation
ADMIN-023 interactive sign-in disabled after documenting dependencies; ADMIN-024 disabled and sessions revoked; remaining interactive privileged accounts had MFA; initial review signed. Alerts configured but not tested; logs retained only 30 days; quarterly access review SOP draft, not yet demonstrated in operation.

Initial illustrative risk score: **20/25 Critical**. Proposed post-action score: **10/25 High**, pending validation and owner approval. The underlying finding stays open for recurring review and monitoring effectiveness. Historical log gaps cannot be retrospectively repaired.
