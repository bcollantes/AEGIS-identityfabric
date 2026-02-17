# AEGIS Alignment with ENS

**Executive Overview (Spanish National Security Scheme – Esquema Nacional de Seguridad)**  
*2026-02-17 — v1.0*

## Executive Overview

The Esquema Nacional de Seguridad (ENS) defines the security principles and control measures required for public-sector and related critical services in Spain. ENS emphasizes governance, risk management, access control, traceability, and continuous improvement.

AEGIS, as an Identity Fabric architecture, strengthens ENS-aligned controls by converging identity governance, privileged access management, policy enforcement, and audit evidence across hybrid and multi-cloud environments. AEGIS contributes directly to ENS domains related to access management, identity lifecycle, logging, and governance.

## Key Contributions

- Centralized identity governance for human and non-human identities (NPAs/HPAs)
- Strong authentication (SSO/MFA) and least privilege enforcement (RBAC, scoped tokens)
- Privileged access governance (JIT), session control, recording, and credential lifecycle (rotation)
- Unified auditability: identity events, policy changes, privileged sessions (SIEM-ready evidence)
- Third-party and operator access governance via controlled, revocable, traceable access paths
- Provider-neutral governance across OpenStack/Azure/AWS/on-prem via standardized connectors

## Alignment Summary Table

| ENS Control Domain (high-level) | AEGIS Contribution | Impact |
|---|---|---|
| Access Control | Federation (SSO/MFA), RBAC, scoped authorization, least privilege | High |
| Identification & Authentication | Strong authentication via IAM/federation layer; consistent identity posture | High |
| Privileged Access | PAM convergence: JIT, session recording, credential rotation, approval workflows | High |
| Logging & Traceability | Immutable audit trails for privileged sessions and identity events; SIEM integration | High |
| Operations Security | Policy enforcement, controlled admin paths, reduced blast radius | Medium–High |
| Governance & Continuous Improvement | Central policy orchestration, evidence generation, maturity roadmap | High |

**Full Technical Annex (Control Mapping Overview)**  
*2026-02-17 — v1.0*

> Disclaimer: ENS includes a broad set of requirements and measures (organizational, operational, and technical). This document provides a practical identity-and-access focused mapping showing how AEGIS supports ENS-aligned controls. It does not replace a formal ENS compliance assessment, risk analysis, or certification process.

## 1. ENS Principles Supported by AEGIS
- Security governance and accountability for identity policy ownership and enforcement.
- Risk reduction via least privilege, SoD, and controlled privileged operations.
- Defense-in-depth by combining federation, lifecycle governance, privileged control, and audit evidence.
- Continuous improvement through measurable identity controls and roadmap-driven maturity.

## 2. Identification, Authentication, and Access Control
- Federated SSO + MFA enforced for workforce and service access (where applicable).
- RBAC and scoped authorization (tokens/roles) enforced consistently across environments.
- Identity lifecycle governance (Joiner/Mover/Leaver) reduces orphaned access and privilege drift.
- NPA governance: controlled creation, rotation, and deprovisioning of non-personal credentials.
- HPA governance: strict privileged role assignment, approvals, and periodic review.

## 3. Privileged Access Governance (PAM Convergence)
- Just-in-Time privileged access with time-bounded elevation and policy approvals.
- Privileged session brokering through controlled entry points (Access Fabric).
- Session recording and command/audit trails for privileged actions.
- Credential rotation and secrets lifecycle integration (provider-agnostic).
- Reduced standing privileges and minimized lateral movement paths.

## 4. Logging, Traceability, and Evidence
- Identity events: authentication, authorization decisions, provisioning changes.
- Privileged audit: session start/stop, commands, target resources, elevation actions.
- Policy change traceability: who changed what, when, with approval metadata.
- SIEM integration readiness (exportable logs, correlation-friendly identifiers).
- Evidence packaging for audits and ENS supervisory reviews.

## 5. Operational Security and Resilience
- Segmentation of admin paths (PAM entry points) reduces blast radius.
- Consistent enforcement reduces configuration drift between clouds and on-prem.
- Improved incident response through high-fidelity privileged audit and identity forensics.
- Support for controlled resilience testing by defining privilege boundaries and access scopes.

## 6. Third-Party and Delegated Administration
- Scoped vendor/operator access with time limits and explicit approvals.
- Revocation and deprovisioning processes integrated into lifecycle controls.
- Full traceability of third-party privileged sessions and actions.
- Reduced dependency on cloud-native admin accounts by centralizing privileged access paths.

## 7. Governance, Maturity, and Continuous Improvement
- Central identity policy governance with measurable objectives and KPIs (e.g., standing privilege reduction).
- Periodic access reviews (particularly HPAs/NPAs) and evidence collection.
- Roadmap-driven maturity: federation consolidation → PAM convergence → provider-neutral access fabric.
- Alignment bridge to ISO 27001, NIST Zero Trust, CIS Controls, and DORA identity expectations.
