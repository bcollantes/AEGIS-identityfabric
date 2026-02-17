# AEGIS Alignment with CIS Controls v8

**Identity & Privileged Access Contribution to CIS Safeguards**  
*2026-02-17 — v1.0*

---

## 1. Executive Overview

The CIS Controls v8 provide a prioritized set of cybersecurity best practices designed to
reduce the most common attack vectors.

AEGIS contributes primarily to the controls related to:

- Identity governance
- Access control
- Privileged account management
- Audit and monitoring
- Credential lifecycle protection

AEGIS does not replace a full CIS implementation program, but it significantly strengthens
identity and privileged access safeguards.

---

## 2. Primary CIS Controls Strengthened by AEGIS

### Control 5 – Account Management

CIS Focus:
- Establish and maintain inventory of accounts
- Disable dormant accounts
- Control lifecycle of identities

AEGIS Contribution:
- Centralized identity lifecycle (Joiner/Mover/Leaver)
- Governance of human and non-human accounts (NPAs/HPAs)
- Deprovisioning workflows
- Periodic review capability

Impact Level: High

---

### Control 6 – Access Control Management

CIS Focus:
- Role-based access
- Least privilege
- Periodic review of access

AEGIS Contribution:
- RBAC policy enforcement
- Scoped authorization tokens
- Centralized policy orchestration
- Privilege revalidation mechanisms

Impact Level: High

---

### Control 7 – Continuous Vulnerability Management (Indirect)

AEGIS does not scan vulnerabilities, but:

- Reduces risk exposure by minimizing standing privileges
- Limits lateral movement through JIT privilege activation

Impact Level: Supporting

---

### Control 8 – Audit Log Management

CIS Focus:
- Collect, alert, and retain logs
- Monitor administrative activity

AEGIS Contribution:
- Privileged session recording
- Command-level traceability
- Identity event logs
- SIEM integration readiness

Impact Level: High

---

### Control 12 – Network Infrastructure Management (Indirect)

AEGIS does not manage firewalls or segmentation directly,
but enforces identity-centric access independent of network trust.

Impact Level: Supporting

---

### Control 16 – Application Software Security (Indirect)

AEGIS strengthens application security posture by:

- Governing service accounts
- Controlling API credential lifecycle
- Reducing credential sprawl

Impact Level: Supporting

---

## 3. High-Level Mapping Table

| CIS Control | AEGIS Capability | Strength |
|-------------|------------------|----------|
| Control 5 – Account Management | Identity lifecycle, deprovisioning, governance | High |
| Control 6 – Access Control | RBAC, scoped policies, least privilege | High |
| Control 8 – Audit Logs | Session recording, identity events | High |
| Control 12 – Network Mgmt | Identity-based trust enforcement | Supporting |
| Control 16 – App Security | Service account governance | Supporting |

---

## 4. What AEGIS Does Not Cover Alone

AEGIS does not natively implement:

- Endpoint detection and response
- Vulnerability scanning
- Network IDS/IPS
- Patch management

These are complementary controls within a full CIS implementation.

---

## 5. Publish-Safe Statement

> AEGIS strengthens CIS Controls v8 implementation by providing centralized identity governance,
least-privilege enforcement, privileged access control, and auditable session management across hybrid environments.

---

## 6. Technical Verdict

CIS Controls v8 strongly emphasize identity and privileged access governance.
AEGIS materially reduces risk exposure in these areas and enhances auditability,
particularly against common attack paths involving compromised credentials and privilege escalation.
