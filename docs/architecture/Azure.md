# AEGIS Integration on Azure Cloud

```
┌──────────────────────────────┐
│        Entra ID (SSO/MFA)    │
└─────────────┬────────────────┘
              │ Federation
              ▼
    ┌──────────────────────────┐
    │  AEGIS IAM (INDIGO+XOMS) │
    └─────────────┬────────────┘
                   │ Policy Sync
                   ▼
    ┌──────────────────────────┐
    │     Azure Key Vault      │
    └─────────────┬────────────┘
                   │
                   ▼
    ┌──────────────────────────┐
    │ Azure Defender / Audit   │
    └──────────────────────────┘
```

**How to interpret it**
- Entra → federation/MFA
- AEGIS → orchestration & policy
- Key Vault → secrets lifecycle
- Defender → privileged monitoring
