---
name: Standards Compliance Tracker
about: Track alignment with DORA / ENS / ISO / NIST / CSF / CIS / PCI / SOC2 / GDPR
labels: compliance, security
---

## 🧮 Standards Compliance Tracker (DORA / ENS / ISO / NIST / CSF / CIS / PCI / SOC 2 / GDPR)

### 🎯 Scope
Monitor and maintain the alignment of AEGIS architecture with international and EU cybersecurity frameworks.

### 🧩 Components in Scope
| Component | Description | Owner | Status |
|------------|-------------|--------|---------|
| INDIGO IAM | Federation, SSO, MFA | Baltasar | 🟢 Compliant |
| XOMS | Identity lifecycle & policy | Baltasar | 🟡 In progress |
| Keystone | OpenStack IAM layer | Baltasar | 🟢 Compliant |
| JumpServer | PAM / Access Fabric Controller | Baltasar | 🟡 In progress |

### Frameworks
- [ ] DORA
- [ ] ENS
- [ ] ISO/IEC 27001:2022
- [ ] NIST SP 800-207 (Zero Trust)
- [ ] NIST CSF 2.0
- [ ] CIS Controls v8
- [ ] PCI DSS 4.0
- [ ] SOC 2 (AICPA)
- [ ] GDPR (EU)

### 📆 Next Actions
- [ ] Add audit evidence references in `/docs/standards`
- [ ] Automate control validation via CI workflow
- [ ] Publish compliance matrix (v1.0)
- [ ] Peer review before certification submission
