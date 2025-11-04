# Final Architecture Vision (Access Fabric)

JumpServer as **Access Fabric Controller** orchestrating authZ/authN/audit across providers.
INDIGO & XOMS remain as federation and identity/policy engines.
Providers (Azure/AWS/On-Prem) expose resources via standard connectors.

*Key: provider-independent access governance with full auditability.*
