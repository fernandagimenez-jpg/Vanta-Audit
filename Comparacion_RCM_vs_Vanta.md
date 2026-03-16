# Comparación RCM 2026 vs Issues Vanta
*Análisis generado: 2026-03-16*

---

## Issues ya cargados en Vanta (visibles en la imagen)

| # | Título en Vanta | Severidad | Estado | Due Date |
|---|-----------------|-----------|--------|----------|
| 1 | Annual Cybersecurity Strategy has not been reviewed or approved | Low | Not started | Mar 31, 2026 |
| 2 | Lack of updates and Reporting of the Cybersecurity Strategy to Governing Committees and the Board | High | Not started | Mar 31, 2026 |
| 3 | Excessive system access (ELC) | Medium | Not started | — |
| 4 | Incomplete Application Access (A&R) | Medium | Not started | — |
| 5 | Incomplete Backup and Insufficient Data Retention Periods | Medium | Not started | — |
| 6 | Incomplete Asset Management Procedures and Standards | Medium | Not started | — |
| 7 | Lack of Formal Stakeholder Engagement and Accountability in Cybersecurity Risk Management | Medium | Not started | — |
| 8 | *(8vo issue - texto no completamente legible en imagen)* | — | — | — |
| 9 | Incomplete Formalization and Immature Governance of Cybersecurity Policies and Standards | High | Not started | — |

---

## Mapeo: Hallazgos RCM → Issues Vanta

### ✅ Ya mapeados / cubiertos en Vanta

| Control RCM | Hallazgo | Issue Vanta correspondiente |
|-------------|----------|-----------------------------|
| **C.Cyber.Gov.01** | Plan Estratégico 2026 no formalmente revisado/aprobado por el Board | Issue #1 ✅ |
| **C.Cyber.Gov.02** | Plan no actualizado; falta reporte a Comités (Cybersecurity, Non-Financial Risk, Audit) | Issue #2 ✅ |
| **C.Cyber.Gov.05** | 75% de riesgos de terceros sin acción; falta clasificación formal de indicadores | Issue #7 ✅ |
| **C.Cyber.Gov.03** | Deficiencias en gobernanza, integridad, propiedad y cobertura de controles en políticas | Issue #9 ✅ |
| **C.Cyber.RM.02** *(parcial)* | Políticas aprobadas solo a nivel Manager; awareness no formal → cubierto por Gov.03 | Issue #9 ✅ (parcial) |
| **C.Cyber.RM.06** *(parcial)* | Framework de políticas incompleto; aprobación insuficiente → cubierto por Gov.03 | Issue #9 ✅ (parcial) |

---

### ❌ Hallazgos RCM SIN issue en Vanta (pendientes de cargar)

A continuación se propone cómo agruparlos para una carga sumarizada:

---

## ISSUES PROPUESTOS PARA CARGAR EN VANTA

> **Nota:** El Issue A original (Policy Framework) ha sido **eliminado** como issue nuevo.
> C.Cyber.Gov.03 ya está cargado en Vanta como *"Incomplete Formalization and Immature Governance of Cybersecurity Policies and Standards"* (Issue #9).
> Los aspectos de políticas/awareness de RM.02 y RM.06 quedan cubiertos por ese issue.
> Los aspectos restantes de RM.02 (Risk Management Policy) y RM.06 (Incident Response/Recovery) se absorben en los Issues C y D respectivamente.

---

### 🔴 ISSUE PROPUESTO B — Gobernanza: Roles y Responsabilidades no Definidos
**Control RCM:** C.Cyber.Gov.04

**Título sugerido:**
> *Incomplete Definition of Cybersecurity Roles, Responsibilities and Key Positions*

**Resumen:**
Si bien la estructura de Ciberseguridad está definida en Workday, sólo están documentadas las responsabilidades del CISO y de los work teams, no las de posiciones clave. Falta segregación de funciones y accountability ejecutiva formal.

**Severidad sugerida:** Medium
**Owner:** CISO / HR

---

### 🔴 ISSUE PROPUESTO C — Risk Management: Ausencia de Proceso Formal de Risk Assessment y Risk Management Policy
**Controles RCM:** C.Cyber.RM.01 · C.Cyber.RM.02 *(aspectos de Risk Mgmt)* · C.Cyber.RM.03 · C.Cyber.RM.04 · C.Cyber.RM.05

**Título sugerido:**
> *Lack of Formal Cybersecurity Risk Assessment Process and Risk Management Policy Integrated with ERM*

**Resumen:**
- No existe un proceso documentado de risk assessment integrado con el ERM (RM.01)
- No se realizaron evaluaciones comprehensivas de likelihood/impact ni linkage con ICFR
- **No se estableció formalmente una Cybersecurity Risk Management Policy** (RM.02 — aspecto no cubierto por Issue #9)
- Risk self-assessments limitados y no alineados con ERM, risk appetite ni estructura de gobernanza aprobada por el Board (RM.02)
- El Global Standard de cifrado/hashing no referencia regulaciones locales; gaps en accountability de vulnerability e incident assessments (RM.03)
- Sin proceso formal de escalación de riesgos (RM.04) ni reporte oportuno a stakeholders (RM.05)

**Severidad sugerida:** High
**Owner:** CISO / Risk Manager

---

### 🟠 ISSUE PROPUESTO D — Vulnerability Management e Incident Response/Recovery: Programa Deficiente
**Controles RCM:** C.Cyber.CVM.01 · C.Cyber.CVM.03 · C.Cyber.CVN.04 · C.Cyber.RM.06 *(aspecto IR/Recovery)*

**Título sugerido:**
> *Continuous Vulnerability Management and Incident Response/Recovery Program – Governance, Tooling and Coverage Gaps*

**Resumen:**
- Dependencia de un único individuo (Cyber Principal) sin equipo formal ni alternativo; key-person risk (CVM.01)
- Actividades de VM reactivas y ad hoc; políticas de VM e Incident Management no formalmente aprobadas por el CISO (CVM.01)
- Inventario de activos de información incompleto; gaps en cloud security, pen testing y marco de risk acceptance (CVM.03)
- No existe inventario centralizado de herramientas de ciberseguridad con owners, alcance e integración definidos (CVN.04)
- **No se estableció un programa de Incident Response & Recovery formalmente aprobado**: sin RTOs, RPOs, DR plan, BCP alineados a sistemas críticos (RM.06 — aspecto no cubierto por Issue #9)
- Riesgo SOX: gaps en incident response comprometen la confiabilidad de sistemas que soportan reportes financieros

**Severidad sugerida:** High
**Owner:** Cyber Principal / CISO

---

### 🟠 ISSUE PROPUESTO E — Red e Infraestructura: Falta de Estándares y Controles Documentados
**Controles RCM:** C.Cyber.NTW.01 · C.Cyber.NTW.3.1 · C.Cyber.NTW.3.3 · C.Cyber.NTW.04 · C.Cyber.NTW.05

**Título sugerido:**
> *Network Security – Missing Standards, Monitoring Controls and Traceability*

**Resumen:**
- No existen estándares formales para VPN (Netskope/Pritunl), firewalls Fortinet, FortiCloud (NTW.01)
- Debilidades en change management, logging y revisión periódica de controles de red (NTW.3.1)
- Evidencia insuficiente para auditar diseño de controles de triage/priorización/remediación (NTW.3.3)
- Sin patching automatizado ni monitoreo para el entorno FortiCloud Log Management (NTW.04)
- Incidentes de seguridad en endpoints (Cortex) sin trazabilidad ni seguimiento formal (NTW.05)

**Severidad sugerida:** High
**Owner:** Network/Infrastructure Team / CISO

---

### 🟡 ISSUE PROPUESTO F — Gobernanza Regional: Desalineación de Políticas en Subsidiarias
**Control RCM:** C.Cyber.NTW.07

**Título sugerido:**
> *Cybersecurity Policy Misalignment Across Subsidiaries – Brazil and Argentina*

**Resumen:**
Las políticas de Seguridad de la Información comunicadas a empleados de Brasil y Argentina no están actualizadas ni alineadas con el framework de gobernanza actual de Kavak. Riesgo de incumplimiento regulatorio local y exposición SOX.

**Severidad sugerida:** Medium
**Owner:** CISO / Legal/Compliance Regional

---

## Resumen Ejecutivo del Gap

| Estado | Cantidad | Controles |
|--------|----------|-----------|
| ✅ Ya en Vanta | 4 issues / 6 controles | Gov.01, Gov.02, Gov.03, Gov.05 + parciales RM.02/RM.06 |
| ❌ Pendientes de cargar | **5 issues agrupados** | Gov.04, RM.01-05 (Risk Mgmt Policy), RM.06 (IR/Recovery), CVM.01/03, CVN.04, NTW.01/3.1/3.3/04/05/07 |
| **Total hallazgos RCM** | **20 controles con finding** | — |

### Controles RCM marcados como "reference" (no duplicar)
- R.Cyber.RM.04 y R.Cyber.RM.05 → referencian a C.Cyber.RM.02 (incluido en Issue Propuesto C)
- C.Cyber.NTW.3.4 → referencia a C.Cyber.NTW.3.1 (incluido en Issue Propuesto E)
- C.Cyber.NTW.06 → referencia a controles de sección 3 (incluidos en Issue Propuesto D/E)

### Cobertura de RM.02 y RM.06 (controles con cobertura dividida)
| Control | Aspecto | Dónde queda cubierto |
|---------|---------|----------------------|
| RM.02 | Políticas aprobadas solo por Manager; awareness informal | Issue #9 ya en Vanta ✅ |
| RM.02 | **Ausencia de Cybersecurity Risk Management Policy; risk self-assessments** | **Issue Propuesto C** |
| RM.06 | Framework de políticas incompleto/inconsistente | Issue #9 ya en Vanta ✅ |
| RM.06 | **Incident Response & Recovery no operacionalizado (RTOs, RPOs, DR, BCP)** | **Issue Propuesto D** |

---

## Priorización sugerida de carga en Vanta

| Prioridad | Issue | Justificación |
|-----------|-------|---------------|
| 1 | Issue C — Risk Assessment + Risk Mgmt Policy | Impacto directo en SOX/IPO readiness; sin proceso formal ni política |
| 2 | Issue D — CVM + Incident Response/Recovery | Key-person risk + VM ad hoc + sin DR/BCP = exposición operacional y SOX alta |
| 3 | Issue E — Network Security | Múltiples controles sin evidencia; riesgo de red no gestionado |
| 4 | Issue B — Roles & Responsibilities | Governance gap que afecta todos los demás |
| 5 | Issue F — Regional Policies | Riesgo regulatorio en Brasil/Argentina |
