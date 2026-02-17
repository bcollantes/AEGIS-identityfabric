# AEGIS Alignment with PCI DSS 4.0

**Identity & Privileged Access Contribution to Payment Security Controls**  
*2026-02-17 — v1.0*

---

## 1. Executive Overview

PCI DSS 4.0 establishes security requirements to protect cardholder data environments (CDE).
Identity and privileged access management are critical to limiting unauthorized access,
reducing lateral movement, and ensuring traceability of administrative actions.

AEGIS contributes primarily to:

- Strong authentication and access control
- Privileged account governance
- Least privilege enforcement
- Audit logging and traceability
- Credential lifecycle management

AEGIS does not replace PCI controls, but it materially strengthens
identity-related requirements within PCI DSS 4.0.

---

## 2. Key PCI DSS 4.0 Requirements Supported by AEGIS

### Requirement 7 – Restrict Access to System Components and Cardholder Data

PCI Focus:
- Role-based access control
- Need-to-know principle
- Access authorization mechanisms

AEGIS Contribution:
- RBAC enforcement
- Scoped policy control
- Centralized access governance
- Privilege minimization

Impact Level: High

---

### Requirement 8 – Identify Users and Authenticate Access

PCI Focus:
- Unique user IDs
- Multi-factor authentication
- Secure authentication mechanisms
- Control of non-console administrative access

AEGIS Contribution:
- Federated identity (SSO/MFA)
- Central authentication broker
- Non-human account governance
- Privileged session gating

Impact Level: High

---

### Requirement 10 – Log and Monitor All Access to System Components

PCI Focus:
- Audit trails for administrative actions
- Log retention and review
- Detection of suspicious activity

AEGIS Contribution:
- Privileged session recording
- Command-level traceability
- Identity event logging
- SIEM integration readiness

Impact Level: High

---

### Requirement 12 – Support Information Security with Organizational Policies

PCI Focus:
- Risk management
- Governance documentation
- Security oversight

AEGIS Contribution:
- Policy enforcement traceability
- Governance reporting
- Evidence packaging for audits

Impact Level: Supporting / High (depending on integration)

---

## 3. High-Level Mapping Table

| PCI DSS Requirement | AEGIS Capability | Strength |
|----------------------|------------------|----------|
| Req. 7 – Access Control | RBAC, least privilege | High |
| Req. 8 – Authentication | SSO, MFA, identity governance | High |
| Req. 10 – Logging | Session recording, audit trails | High |
| Req. 12 – Governance | Policy traceability, reporting | Supporting |

---

## 4. Important Clarification

AEGIS does not:

- Encrypt cardholder data
- Perform network segmentation
- Provide vulnerability scanning
- Replace PCI compliance programs

AEGIS strengthens the identity and privileged control layer
within a PCI DSS 4.0-aligned security architecture.

---

## 5. Publish-Safe Statement

> AEGIS strengthens PCI DSS 4.0-aligned environments by enforcing strong authentication,
least privilege, privileged session control, and auditable administrative operations
across hybrid infrastructures.

---

## 6. Technical Verdict

Credential compromise and privilege escalation are primary causes of PCI breaches.
AEGIS materially reduces this risk by:

- Minimizing standing administrative privileges
- Enforcing multi-factor authentication
- Providing centralized privileged session control
- Ensuring high-fidelity auditability

AEGIS acts as a hardened identity control plane within PCI DSS 4.0 environments.

