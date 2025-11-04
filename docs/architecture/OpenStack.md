# AEGIS Core Architecture (OpenStack)

```
┌──────────────────────────┐
│        User / API        │
│ (Human or Service Auth)  │
└────────────┬─────────────┘
             │  Login (SSO/MFA)
             ▼
    ┌────────────────────┐
    │     INDIGO IAM     │
    │ (Federation & SSO) │
    └─────────┬──────────┘
              │  SCIM / OIDC
              ▼
    ┌────────────────────┐
    │       XOMS         │
    │ (Identity Manager) │
    └─────────┬──────────┘
              │  Provision / Policy Sync
              ▼
    ┌────────────────────┐
    │     Keystone       │
    │ (OpenStack IAM)    │
    └─────────┬──────────┘
              │  Role/Token Validation
              ▼
    ┌────────────────────┐
    │   JumpServer PAM   │
    │ (Privileged Access)│
    └─────────┬──────────┘
              │
              ▼
    ┌────────────────────┐
    │   Target Systems   │
    │ (VMs, DBs, APIs…)  │
    └────────────────────┘
```

**How to interpret it**
- INDIGO → federation/SSO/MFA
- XOMS → lifecycle & policy (SCIM)
- Keystone → central RBAC/tokens
- JumpServer → JIT PAM, recording, rotation
