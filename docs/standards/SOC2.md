# AEGIS Alignment with SOC 2

**Identity & Privileged Access Contribution to SOC 2 Trust Services Criteria (TSC)**  
*2026-02-18 — v1.0*

---

## 1. Executive Overview

SOC 2 reports assess how an organization designs and operates controls aligned with the
AICPA Trust Services Criteria (TSC). SOC 2 commonly focuses on the Security category,
and may also include Availability, Confidentiality, Processing Integrity, and Privacy.

AEGIS contributes primarily to SOC 2 by strengthening identity governance, access control,
privileged access management, and auditability. These capabilities support multiple SOC 2
control expectations related to logical access, monitoring, change traceability, and incident response evidence.

AEGIS is not a SOC 2 certification by itself. SOC 2 applies to an organization's control environment,
processes, and evidence. AEGIS provides technical control capabilities that can materially support SOC 2 readiness.

---

## 2. SOC 2 Trust Services Criteria — Where AEGIS Fits

### 2.1 Security (Common Criteria – CC)

This is the core for most SOC 2 reports.

AEGIS strengthens Security by enabling:

- Strong authentication (SSO/MFA, federation)
- Least privilege (RBAC, scoped authorization)
- Privileged access governance (JIT elevation, approvals)
- Session control and recording for administrative actions
- Centralized identity lifecycle management (JML)
- Audit evidence and SIEM integration readiness

**Impact Level:** High

---

### 2.2 Availability (A)

Availability controls focus on system uptime, resilience, and incident response.

AEGIS supports Availability indirectly by:

- Reducing identity-driven incidents (credential abuse, privilege escalation)
- Improving incident response and containment through rapid access revocation
- Providing high-fidelity privileged audit evidence for operational recovery

**Impact Level:** Supporting / Medium

---

### 2.3 Confidentiality (C)

Confidentiality controls focus on protecting sensitive information from unauthorized disclosure.

AEGIS supports Confidentiality by:

- Restricting access using RBAC and least privilege
- Limiting standing administrative privileges (JIT)
- Controlling access to sensitive systems through a privileged access fabric
- Enforcing traceability on privileged access to confidential datasets

**Impact Level:** High

---

### 2.4 Processing Integrity (PI)

Processing Integrity focuses on system processing being complete, valid, accurate, timely, and authorized.

AEGIS supports Processing Integrity indirectly by:

- Ensuring only authorized identities (including service accounts) can execute sensitive workflows
- Enforcing policy-based privilege boundaries
- Providing auditability for actions impacting processing workflows

**Impact Level:** Supporting

---

### 2.5 Privacy (P)

Privacy controls relate to personal information handling and privacy notice compliance.

AEGIS supports Privacy indirectly by:

- Reducing over-privileged access to personal data systems
- Improving access traceability and accountability
- Supporting GDPR-style accountability principles (evidence-ready access governance)

**Impact Level:** Supporting / Medium

---

## 3. High-Level Mapping Table (SOC 2 TSC)

| SOC 2 Category | AEGIS Capability | Strength |
|---|---|---|
| Security (CC) | MFA/SSO, RBAC, JIT privileged access, session recording, audit trails | High |
| Availability (A) | Rapid containment via revocation, privileged traceability | Medium |
| Confidentiality (C) | Least privilege + controlled admin paths | High |
| Processing Integrity (PI) | Authorized workflow execution + traceability | Supporting |
| Privacy (P) | Access accountability and minimization | Supporting |

---

## 4. Evidence Readiness (Why AEGIS Helps SOC 2)

SOC 2 depends heavily on evidence. AEGIS supports evidence collection by generating:

- Identity events (authentication, authorization, provisioning changes)
- Privileged session logs and recordings
- Policy change traceability (who/what/when)
- Review-ready access governance artifacts (HPA/NPA governance)

This directly reduces the operational burden of audits and improves control defensibility.

---

## 5. What AEGIS Does Not Cover Alone

AEGIS does not replace:

- Organizational policies and governance processes
- Vendor management programs
- Business continuity / disaster recovery orchestration
- Vulnerability and patch management
- Security awareness training

AEGIS is a strong technical control component within a full SOC 2 readiness program.

---

## 6. Publish-Safe Statement

> AEGIS strengthens SOC 2 readiness by providing centralized identity governance, least-privilege enforcement,
privileged access control, and audit-grade traceability across hybrid environments—supporting the design and operation
of controls aligned with the SOC 2 Trust Services Criteria.

---

## 7. Technical Verdict

SOC 2 success often depends on proving “logical access control” and “accountability” with strong evidence.
AEGIS materially improves SOC 2 control effectiveness by:

- reducing standing privilege,
- enforcing MFA/SSO and RBAC,
- centralizing privileged access pathways,
- providing audit-grade logs and session evidence.

