# AEGIS Alignment with DORA

**Executive Overview (Digital Operational Resilience Act – EU 2022/2554)**  
*2026-02-17 — v1.0*


The Digital Operational Resilience Act (DORA) establishes a unified framework for ICT risk management,
incident reporting, operational resilience testing, and third-party risk governance within EU financial entities.

AEGIS, as an Identity Fabric architecture, strengthens the identity and access governance layer required
for DORA-aligned operational resilience.


## Key Contributions

- Centralized identity governance (human + non-human identities)
- Strict RBAC and Separation of Duties enforcement
- Just-in-Time privileged access and session recording
- Immutable audit trail and identity event logging
- Scoped third-party access control
- Multi-cloud identity governance consistency

## Alignment Summary Table

| DORA Domain | AEGIS Contribution | Impact |
|---|---|---|
| ICT Risk Management | Lifecycle control, RBAC, policy enforcement | High |
| Privileged Access Control | PAM layer, JIT access, recording | High |
| Incident Response | Traceability and audit fabric | High |
| Resilience Testing | Identity segmentation and scope reduction | Medium–High |
| Third-Party Risk | Scoped vendor access governance | High |
| Governance | Central policy orchestration and accountability | High |

## ICT Risk Management (Articles 5–16)
- Identity lifecycle management (JML processes).
- NPA and HPA governance.
- Centralized policy propagation across environments.
- Role-based access control and privilege minimization.

## Access Control & Privileged Governance
- Federated SSO and MFA enforcement.
- Privileged Access Management convergence.
- Session recording and credential rotation.
- Token-based scoped authorization.

## Incident Detection & Reporting (Articles 17–23)
- Identity event logging.
- Privileged session audit trails.
- Policy change traceability.
- SIEM integration capability.

## Operational Resilience Testing (Articles 24–27)
- Segmented identity domains.
- Reduced blast radius via JIT access.
- Controlled privilege escalation paths.
- Testable policy enforcement.

## ICT Third-Party Risk (Articles 28–44)
- Temporary scoped vendor accounts.
- Full auditability of third-party sessions.
- Centralized revocation.
- Reduced persistent privileged exposure.

## Governance & Accountability
- Policy ownership mapping.
- Separation of duties controls.
- Compliance evidence generation.
- Alignment with ISO 27001 / NIST / CIS.