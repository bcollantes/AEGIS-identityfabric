# AEGIS Integration on AWS Cloud

```
┌──────────────────────────────────┐
│ AWS IAM Identity Center (SSO)    │
└─────────────┬────────────────────┘
              │ Federation
              ▼
    ┌──────────────────────────┐
    │  AEGIS IAM (INDIGO+XOMS) │
    └─────────────┬────────────┘
                   │ Policy Sync
                   ▼
    ┌──────────────────────────┐
    │  AWS Secrets Manager     │
    └─────────────┬────────────┘
                   │
                   ▼
    ┌──────────────────────────┐
    │ Control Tower / Audit    │
    └──────────────────────────┘
```

**How to interpret it**
- IAM Identity Center → SSO
- AEGIS → unified provisioning/policy
- Secrets Manager → NPA credentials
- Control Tower/CloudTrail → governance
