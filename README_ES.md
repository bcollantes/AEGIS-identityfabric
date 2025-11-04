# 🛡️ AEGIS — Arquitectura Abierta de Identidad y Gobierno

**AEGIS** es una arquitectura de referencia abierta para **IAM/PAM** en entornos **híbridos y multi-cloud**.
Integra **OpenStack Keystone**, **INDIGO IAM**, **XOMS** y **JumpServer** para construir un **Access Fabric Zero Trust** independiente del proveedor.

## 🎯 Objetivos
- SSO y MFA federados (OIDC/SAML2)
- Ciclo de vida centralizado (SCIM) para Usuarios, NPAs y HPAs
- PAM con JIT, grabación de sesión y rotación de credenciales
- Orquestación de políticas cross-cloud (OpenStack, Azure, AWS)
- Auditabilidad total y alineación con **DORA / ENS / ISO 27001 / NIST 800-207**

## 🧩 Componentes
- **INDIGO IAM** — Federación, SSO, MFA
- **XOMS** — Ciclo de vida de identidades y políticas (SCIM)
- **Keystone (OpenStack)** — Autoridad central de tokens y RBAC
- **JumpServer** — Acceso privilegiado y Access Fabric Controller

## 🗺️ Roadmap (2025–2027)
- **Q4 2025** – Inicio y gobierno del proyecto
- **Q1–Q2 2026** – Consolidación IAM/PAM y federación
- **Q3–Q4 2026** – Piloto de Access Fabric con JumpServer
- **Q1–Q2 2027** – Expansión de conectores multi-cloud
- **Q3–Q4 2027** – Preparación de certificaciones (ENS Alto / ISO 27001)

## 📚 Documentación
Ver `docs/`:
- `architecture/` — diagramas base e integraciones cloud
- `standards/` — mapeo DORA / ENS / ISO 27001 / NIST 800-207
- `governance/` — framework de seguridad, riesgo y roles

## 🤝 Contribuciones
Se agradecen issues, debates y PRs. Revisa `CONTRIBUTING.md` y `CODE_OF_CONDUCT.md`.

---
© 2025 Baltasar Collantes Giner — AEGIS Technical Owner / IAM–PAM Security Architect · baltasar.collantesginer@gmx.es · November 2025
Licencia Apache 2.0. Ver `LICENSE`.
