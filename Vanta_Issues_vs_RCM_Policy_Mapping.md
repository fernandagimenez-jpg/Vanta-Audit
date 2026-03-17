# Vanta Issues ↔ RCM Audit Report — Policy Mapping

**Date:** March 17, 2026
**Scope:** IT Cybersecurity Audit 2026 — Kavak
**Source documents:**
- Vanta Issues (13 open issues — updated screenshot)
- RCM Audit Report: `Copia COMPARTIDA de IT Cyber - RCM - 2026.xlsx` (sheets: `IT - RCM` & `Cyber - DE`)

**Owner key:** DC = David Cirielli, CISO | OG = OG (see Vanta profile — IT Operations)

---

## Master Mapping Table

| # | Vanta Issue | Severity | Vanta Status | Vanta Owner | RCM Control(s) | RCM Issue # | Suggested Deadline |
|---|---|---|---|---|---|---|---|
| 1 | Annual Cybersecurity Strategy has not been reviewed or approved | Low | Not started | DC | C.Cyber.Gov.01 | — | **Mar 31, 2026** ✅ |
| 2 | Lack of Updates and Reporting of the Cybersecurity Strategy to Governance Committees and the Board | Low | Not started | DC | C.Cyber.Gov.02 | — | **Mar 31, 2026** ✅ |
| 3 | Incomplete Asset Inventory and Lack of a Unified Source of Truth | High | Not started | OG | C.Cyber.CVM.03 · C.Cyber.CVN.04 | **#3 · #4** | **Jun 30, 2026** ⬅ |
| 4 | Excessive system access risk (ELC-R34) | Medium | Not started | DC | C.Cyber.CVN.05 · C.Cyber.NTW.06 | — | **Jun 30, 2026** ⬅ |
| 5 | Lack of an Actionable Implementation BCP & DRP | Medium | Not started | OG | C.Cyber.RM.06 | — | **Jun 30, 2026** ⬅ |
| 6 | Incomplete Backups and Insufficient Data Retention Periods | Medium | Not started | OG | C.Cyber.NTW.05 | — | **Jun 30, 2026** ⬅ |
| 7 | Lack of Formal Stakeholder Engagement and Accountability in Cybersecurity Risk Management | Medium | Not started | DC | C.Cyber.Gov.05 · C.Cyber.RM.01 | — | **Jun 30, 2026** ⬅ |
| 8 | Incomplete and Unapproved Cybersecurity Policy Framework | High | **In progress** | DC | C.Cyber.Gov.03 · C.Cyber.RM.02 · C.Cyber.RM.03 | **#1** (partial) | **Jun 30, 2026** ⬅ urgent |
| 9 | Incomplete Definition of Cybersecurity Roles, Responsibilities and Key Positions | Medium | Not started | DC | C.Cyber.Gov.04 | — | **Jun 30, 2026** ⬅ |
| 10 | Lack of Formal Cybersecurity Risk Assessment Process Integrated with ERM | High | Not started | DC | C.Cyber.RM.01 · C.Cyber.RM.03 | — | **Jun 30, 2026** ⬅ |
| 11 | Continuous Vulnerability Management Program – Governance, Tooling and Coverage Gaps | High | Not started | DC | C.Cyber.CVM.01 · C.Cyber.CVM.02 | **#1 · #2** | **Jun 30, 2026** ⬅ |
| 12 | Network Security – Missing Standards, Monitoring Controls and Traceability | High | Not started | DC | C.Cyber.NTW.01 · C.Cyber.NTW.3.1 · C.Cyber.NTW.3.4 · C.Cyber.EUC.03 | — | **Sep 30, 2026** ⬅ |
| 13 | Cybersecurity Policy Misalignment Across Subsidiaries – Brazil and Argentina | Medium | Not started | DC | C.Cyber.NTW.07 | — | **Sep 30, 2026** ⬅ |

> ✅ = Deadline already set in Vanta | ⬅ = Suggested deadline | **Issues 3, 8, 10, 11 have no deadline set in Vanta yet — add immediately (High severity + SOX 404 impact)**

---

## RCM Formal Issues Cross-Reference

| RCM Issue # | RCM Control | RCM Priority | RCM Finding Summary | Linked Vanta Issue(s) |
|---|---|---|---|---|
| **#1** | C.Cyber.CVM.01 | High | No comprehensive, formally approved Cybersecurity Policy framework | **#8** + **#11** |
| **#2** | C.Cyber.CVM.02 | High | Key-person dependency in CVM; no formal team, no talent framework | **#11** |
| **#3** | C.Cyber.CVM.03 | High | No centralized asset inventory; cloud security governance gaps; no pen testing | **#3** |
| **#4** | C.Cyber.CVN.04 | High | No centralized cybersecurity tool inventory; lifecycle management gaps | **#3** |

> All 4 formal RCM issues are **High priority** and owned by **David Cirielli, CISO**.
> None of them currently have a remediation deadline set in Vanta.

---

## Detailed Issue Breakdowns

---

### Issue #1 — Annual Cybersecurity Strategy has not been reviewed or approved
**Severity:** Low | **Owner:** David Cirielli, CISO | **Status:** Not started | **Due:** Mar 31, 2026

**Vanta Controls:** —
**RCM Control:** `C.Cyber.Gov.01` — Governance / 1.1 Strategy & Objective

**RCM Audit Finding (Cyber-DE Row 2 · Passed: N):**
> The 2026 Cybersecurity Strategic Plan has been developed by the CISO but has **not been formally reviewed or approved by the Board of Directors**. The strategy is based on a 2025 Risk Appetite Statement informally agreed with prior executive management and not validated or updated to reflect current governance and risk context.

**Recommendation:** Finalize and obtain formal Board-level approval for the 2026 Cybersecurity Strategic Plan. Update the Risk Appetite Statement and align it with current enterprise governance structures.

**Policy linkage:** Cybersecurity Strategy Policy · Board Governance Framework

---

### Issue #2 — Lack of Updates and Reporting to Governance Committees and the Board
**Severity:** Low | **Owner:** David Cirielli, CISO | **Status:** Not started | **Due:** Mar 31, 2026

**Vanta Controls:** —
**RCM Control:** `C.Cyber.Gov.02` — Governance / 1.1 Strategy & Objective

**RCM Audit Finding (Cyber-DE Row 3 · Passed: N):**
> Although monthly cybersecurity presentations are made to the CTO, the Cybersecurity Strategic Plan has not been updated and **compliance issues have not been reported to the Cybersecurity Committee, the Non-Financial Risk Committee, or the Audit Committee**. Communication and update meetings on general Cybersecurity topics were not held with governance bodies during the review period.

**Recommendation:** Implement a formal quarterly reporting cadence to all relevant governance committees. Formally update the Strategic Plan before next committee cycle.

**Policy linkage:** Cybersecurity Governance Reporting Policy · Committee Charter

---

### Issue #3 — Incomplete Asset Inventory and Lack of a Unified Source of Truth
**Severity:** High | **Owner:** OG | **Status:** Not started | **Due:** *(not set)*

**Vanta Controls:** VPM-42 · AST-4 (+2)
**RCM Controls:**
- `C.Cyber.CVM.03` — **RCM Issue #3** (High) — CVM / 3.3 Monitoring & Reporting
- `C.Cyber.CVN.04` — **RCM Issue #4** (High) — CVM / 3.4 Lifecycle Management

**RCM Audit Finding — Issue #3 (Cyber-DE Row 17 · Passed: N):**
> The Cybersecurity function does **not maintain a complete, accurate, and centrally governed inventory of information assets**, including cloud environments. Deficiencies include: asset inventory completeness, cloud security governance, no formal penetration testing coverage plan, no risk acceptance framework, and absence of monitoring KPIs.

**RCM Audit Finding — Issue #4 (Cyber-DE Row 18 · Passed: N):**
> The Cybersecurity function does **not maintain a formally documented and centrally governed inventory of cybersecurity tools**, including ownership, administrators, scope of coverage, and integration points for monitoring, vulnerability management, and incident response. The tool inventory was reconstructed through independent review, confirming there is no consolidated register.

**Recommendation:** Establish a single, centrally governed asset inventory (hardware, software, cloud, SOX-relevant systems) and a separate cybersecurity tool registry. Assign clear ownership. Reconcile quarterly.

**Policy linkage:** Asset Management Policy · Cloud Security Policy · Vulnerability Management Procedures
**Suggested Owner (remediation):** OG (Vanta) — consider involving David Cirielli, CISO for CVM tooling component
**Suggested Deadline:** **June 30, 2026** — *(2 formal High-priority RCM issues; no Vanta deadline set)*

---

### Issue #4 — Excessive System Access Risk (ELC-R34)
**Severity:** Medium | **Owner:** David Cirielli, CISO | **Status:** Not started | **Due:** *(not set)*

**Vanta Controls:** IAC-147 · IAC-146 (+1)
**RCM Controls:**
- `C.Cyber.CVN.05` — CVM / Access Management (marked N/A in DE — pending full review)
- `C.Cyber.NTW.06` — Network / Network Communication Controls (access restrictions, VPN/ZTNA)

**Vanta Description:** The User Access Review (UAR) process is not performed consistently across systems. Excessive access in Active Directory (AD) connectivity groups identified.

**Context from RCM:** While not directly captured as a standalone finding in the Cyber-DE (the UAR/access management controls are marked for review under the Network & Infrastructure subprocess), the `C.Cyber.Gov.04` finding confirms an underlying governance gap:
> "Only the responsibilities of the CISO and work teams are defined, not those of key positions" — preventing enforcement of least-privilege access principles based on role-specific requirements.

**Recommendation:** Conduct an immediate access review across all AD groups with broad memberships. Implement a formal UAR cycle (at minimum semi-annual). Define and enforce least-privilege access aligned with documented role requirements (`C.Cyber.Gov.04` remediation).

**Policy linkage:** Access Management Policy · Identity & Privilege Management · UAR Procedures
**Suggested Deadline:** **June 30, 2026**

---

### Issue #5 — Lack of an Actionable Implementation BCP & DRP
**Severity:** Medium | **Owner:** OG | **Status:** Not started | **Due:** *(not set)*

**Vanta Controls:** BCD-1 · BCD-2 (+1)
**RCM Control:** `C.Cyber.RM.06` — Risk Management / 2.6 Incident Response and Recovery Process

**RCM Audit Finding (Cyber-DE Row 13 · Passed: N):**
> The Company has **not established or fully implemented a comprehensive, formally approved Cybersecurity Policy framework**. Cybersecurity policies, standards, and procedures — including those governing incident response and recovery — remain incomplete, inconsistently approved, and not formally communicated. Documents are in draft or approved only at management level, not by executive or governance bodies.
>
> This directly impacts the existence and enforceability of a formal Business Continuity Plan (BCP) and Disaster Recovery Plan (DRP), which require an approved policy framework as their foundation.

**Recommendation:** Develop and formally approve a standalone BCP and DRP aligned with recognized frameworks. Conduct a Business Impact Analysis (BIA). Test BCP/DRP at least annually. Escalate for Board-level approval as part of the broader policy framework remediation (Vanta Issue #8).

**Policy linkage:** Business Continuity Policy · Disaster Recovery Plan · Incident Response Procedures
**Suggested Owner (remediation):** OG (operational BCP/DRP owner) + David Cirielli, CISO (policy framework sign-off)
**Suggested Deadline:** **June 30, 2026**

---

### Issue #6 — Incomplete Backups and Insufficient Data Retention Periods
**Severity:** Medium | **Owner:** OG | **Status:** Not started | **Due:** *(not set)*

**Vanta Controls:** BCD-44
**RCM Control:** `C.Cyber.NTW.05` — Network / 4.4 Lifecycle Management (FortiCloud)

**RCM Audit Finding (Cyber-DE Row 29 · Passed: N):**
> **Lack of Automated Patching and Monitoring Controls for FortiCloud Log Management Environment.** Deficiencies identified:
> - FortiCloud is running an outdated version with no automated patch management
> - Required licensing gaps limit log coverage and retention capabilities
> - No automated alerting for patch status failures or service disruptions
> - Operational monitoring of log completeness and availability is immature
>
> This directly impacts the integrity, completeness, and availability of log data required for SOX evidence, forensic investigation, and regulatory retention obligations.

**Recommendation:** Implement automated patch management for FortiCloud. Resolve licensing gaps. Establish formal data retention schedules aligned with SOX requirements (minimum 7 years for financial system logs). Set automated alerting for log availability failures.

**Policy linkage:** Backup & Recovery Policy · Data Retention Policy · Log Management Procedures
**Suggested Owner (remediation):** OG (infrastructure) + Ezequiel Tavella, Cybersecurity Manager (FortiCloud oversight)
**Suggested Deadline:** **June 30, 2026**

---

### Issue #7 — Lack of Formal Stakeholder Engagement and Accountability in Cybersecurity Risk Management
**Severity:** Medium | **Owner:** David Cirielli, CISO | **Status:** Not started | **Due:** *(not set)*

**Vanta Controls:** RSK-31 · RSK-22
**RCM Controls:**
- `C.Cyber.Gov.05` — Governance / 1.4 Stakeholder Engagement
- `C.Cyber.RM.01` — Risk Management / 2.1 Risk Assessment
- `C.Cyber.RM.04` — Risk Management / 2.4 Escalation of Risks *(references RM.02)*
- `C.Cyber.RM.05` — Risk Management / 2.5 Timely Communication & Reporting *(references RM.02)*

**RCM Audit Finding — Gov.05 (Cyber-DE Row 6 · Passed: N):**
> A review of the risk register (Sep 2025 – Jan 2026) identified that **approximately 75% of risks associated with third parties remain pending escalation or formal treatment decisions**. Stakeholder ownership and escalation paths for cybersecurity risks are not consistently defined or enforced.

**RCM Audit Finding — RM.01 (Cyber-DE Row 8 · Passed: N):**
> The Company **has not established a formal, documented cybersecurity risk assessment process** fully integrated with the ERM framework. No comprehensive periodic risk assessment has been performed. Risk appetite elements exist in the 2026 strategy but are not operationalized in a structured process with defined owners and escalation thresholds.

**Recommendation:** Define and implement a formal cybersecurity risk management process integrated with ERM. Establish documented RACI for risk ownership and escalation. Resolve third-party risk backlog. Report status to governance committees quarterly.

**Policy linkage:** Cybersecurity Risk Management Policy · Third-Party Risk Policy · ERM Integration Framework
**Suggested Deadline:** **June 30, 2026**

---

### Issue #8 — Incomplete and Unapproved Cybersecurity Policy Framework
**Severity:** High | **Owner:** David Cirielli, CISO | **Status:** ⚡ **In progress** | **Due:** *(not set — add urgently)*

**Vanta Controls:** RSK-103 · GOV-88 (+3)
**RCM Controls:**
- `C.Cyber.Gov.03` — Governance / 1.2 Policies and Procedures
- `C.Cyber.RM.02` — Risk Management / 2.2 Risk Management
- `C.Cyber.RM.03` — Risk Management / 2.3 Accountability & Responsibility
- Directly linked to **RCM Issue #1** (C.Cyber.CVM.01, High)

**RCM Audit Finding — Gov.03 (Cyber-DE Row 4 · Passed: N):**
> "Not all cybersecurity documents are formally approved; they are under review prior to final approval. **Official documents are not available in English or local languages.** Some policies are approved only by the Cybersecurity Manager (not the CISO). Coverage gaps exist across encryption, endpoint security, and other domains."

**RCM Audit Finding — RM.02 (Cyber-DE Row 9 · Passed: N):**
> "Management has **not formally approved (CISO) or consistently applied** cybersecurity policies, risk management processes, and awareness controls. Policies at various stages of drafting, review, approval, and communication — approved only by the Cybersecurity Manager rather than the CISO or governance bodies."

**RCM Audit Finding — Issue #1 / RM.06 (Cyber-DE Row 13 · Passed: N):**
> "The Company has not established or fully implemented a **comprehensive, formally approved Cybersecurity Policy framework**. Policies remain incomplete, inconsistently approved, and not formally communicated across the organization."

**Recommendation:** Complete the policy framework as the highest-priority remediation. Obtain CISO and governance-level approval for all policies. Translate and publish in all required languages. Define an annual review cycle with assigned document owners. This issue is already In Progress — a formal deadline must be set to maintain SOX 404 evidence.

**Policy linkage:** Information Security Policy · All Cybersecurity sub-policies, standards, and procedures
**Suggested Deadline:** **June 30, 2026** *(In Progress — deadline required immediately to close within H1 2026)*

---

### Issue #9 — Incomplete Definition of Cybersecurity Roles, Responsibilities and Key Positions
**Severity:** Medium | **Owner:** David Cirielli, CISO | **Status:** Not started | **Due:** *(not set)*

**Vanta Controls:** GOV-69 · HRS-94 (+2)
**RCM Control:** `C.Cyber.Gov.04` — Governance / 1.3 Roles and Responsibilities

**RCM Audit Finding (Cyber-DE Row 5 · Passed: N):**
> "While the Cybersecurity structure is formally established in Workday, **only the responsibilities of the CISO and work teams are defined, not those of key positions**. Specific requirements, experience levels, and certifications for individual roles are not documented. Only general competencies are provided."

**Recommendation:** Define and formally document role-specific responsibilities, competency requirements, and certification expectations for all key cybersecurity positions supporting ICFR. Publish in Workday and integrate with onboarding. This also directly enables enforcement of least-privilege access controls (Vanta Issue #4).

**Policy linkage:** Cybersecurity Organizational Structure Policy · HR Security Policy · Job Description Framework
**Suggested Deadline:** **June 30, 2026**

---

### Issue #10 — Lack of Formal Cybersecurity Risk Assessment Process Integrated with ERM
**Severity:** High | **Owner:** David Cirielli, CISO | **Status:** Not started | **Due:** *(not set)*

**Vanta Controls:** RSK-25 · RSK-27 (+4)
**RCM Controls:**
- `C.Cyber.RM.01` — Risk Management / 2.1 Risk Assessment
- `C.Cyber.RM.03` — Risk Management / 2.3 Accountability & Responsibility

**RCM Audit Finding — RM.01 (Cyber-DE Row 8 · Passed: N):**
> "The Company **has not established a formal, documented cybersecurity risk assessment process** fully integrated with the ERM framework. No comprehensive and periodic cybersecurity risk assessment has been performed, including identification, assessment of likelihood and impact, and prioritization. Risk appetite is defined in the 2026 strategy but not operationalized in a structured methodology."

**Recommendation:** Design, document, and implement a formal cybersecurity risk assessment methodology aligned with the Company's ERM framework and COSO ERM principles. Require at minimum annual assessments with documented outputs. Obtain Audit Committee visibility.

**Policy linkage:** Cybersecurity Risk Assessment Methodology · ERM Integration Policy · Risk Appetite Framework
**Suggested Deadline:** **June 30, 2026**

---

### Issue #11 — Continuous Vulnerability Management Program – Governance, Tooling and Coverage Gaps
**Severity:** High | **Owner:** David Cirielli, CISO | **Status:** Not started | **Due:** *(not set)*

**Vanta Controls:** VPM-61 · VPM-43
**RCM Controls:**
- `C.Cyber.CVM.01` — **RCM Issue #1** (High) — CVM / Internal Controls & Vendor-based Controls
- `C.Cyber.CVM.02` — **RCM Issue #2** (High) — CVM / Training & Awareness (talent/team)

**RCM Audit Finding — Issue #1 (Cyber-DE Row 15 · Passed: N):**
> "The CVM process identified deficiencies in governance, resourcing, tooling, and control completeness. The function is **dependent on a single key individual (Cyber Principal), with no formally established team or defined alternate** — creating a key-person dependency risk. Vulnerability Management and Incident Management policies **have not been formally approved by the CISO**, limiting enforceability and audit relevance."

**RCM Audit Finding — Issue #2 (C.Cyber.CVM.02 — Talent / Team Structure):**
> CVM function has no formal talent management framework: no defined role requirements, no certification tracking, and no structured onboarding for CVM personnel. The single-person dependency compounds the risk from Issue #1.

**Recommendation:**
(i) Formally approve Vulnerability Management and Incident Management policies.
(ii) Establish a dedicated CVM team with defined roles, backup personnel, and escalation paths.
(iii) Eliminate key-person dependency through documented procedures and cross-training.
(iv) Implement tooling coverage across all in-scope asset classes.

**Policy linkage:** Vulnerability Management Policy · Incident Management Policy · CVM Program Charter
**Suggested Deadline:** **June 30, 2026** *(2 formal High-priority RCM Issues — highest remediation urgency after Issue #8)*

---

### Issue #12 — Network Security – Missing Standards, Monitoring Controls and Traceability
**Severity:** High | **Owner:** David Cirielli, CISO | **Status:** Not started | **Due:** *(not set)*

**Vanta Controls:** —
**RCM Controls:**
- `C.Cyber.NTW.01` — Network / 4.1 Internal Controls & Vendor-based Controls (High)
- `C.Cyber.NTW.3.1` — Network / Change Management & Monitoring (High)
- `C.Cyber.NTW.3.4` — Network / Security Change Management (High)
- `C.Cyber.EUC.03` — Endpoint Security / Monitoring & Reporting

**RCM Audit Finding — NTW.01 (Cyber-DE Row 23 · Passed: N):**
> "**No formal standards were identified for VPN solutions (Netskope and Pritunl), Fortinet firewalls, IPS, FortiCloud, or VLAN segmentation rules.** Configuration baselines are not documented. The Company has not established formally approved standards governing the configuration and operation of key network security technologies."

**RCM Audit Finding — NTW.3.1 / NTW.3.4 (Cyber-DE Row 25 · Passed: N):**
> "**Weaknesses in Network Security Change Management, Logging, and Periodic Review Controls.** Fortinet firewall configuration changes are not consistently authorized, documented, or reviewed. Log monitoring gaps identified. No periodic security configuration review process for VLANs or IPS."

**RCM Audit Finding — EUC.03 (Cyber-DE Row 30 · Passed: N):**
> "**Security incidents detected on endpoints through the Cortex platform are not consistently recorded or traceable** within the organization's formal incident management system. Cortex alerts cannot be systematically reconciled with incident records, creating an audit trail gap."

**Recommendation:**
(i) Document and approve formal network security standards (VPN, firewall, IPS, FortiCloud, VLAN).
(ii) Implement a formal network change management process with mandatory authorization, logs, and periodic review.
(iii) Integrate Cortex endpoint alerts with the incident management system to ensure full traceability for SOX audit evidence.

**Policy linkage:** Network Security Standards · Change Management Policy · Incident Traceability Procedures
**Suggested Owner:** David Cirielli, CISO + **Ezequiel Tavella, Cybersecurity Manager** (co-owner for NTW controls)
**Suggested Deadline:** **September 30, 2026** *(high severity but requires network standards design + system integration lead time)*

---

### Issue #13 — Cybersecurity Policy Misalignment Across Subsidiaries – Brazil and Argentina
**Severity:** Medium | **Owner:** David Cirielli, CISO | **Status:** Not started | **Due:** *(not set)*

**Vanta Controls:** RSK-103 · CPL-119 (+3)
**RCM Control:** `C.Cyber.NTW.07` — Network / 4.7 Network Communication Controls

**RCM Audit Finding (Cyber-DE Row 32 · Passed: N):**
> "**Misalignment Between Cybersecurity Policies and Current Governance Framework — Brazil and Argentina.** Policies communicated to employees in Brazil and Argentina do not reflect current Kavak's Information Security Governance framework. Deficiencies in both countries related to the currency and alignment of cybersecurity policies — including onboarding documentation and acceptable use of technology resources — were identified."

**Recommendation:** Conduct a full review of cybersecurity policies distributed to employees in Brazil and Argentina. Align with the current global governance framework. Translate and re-communicate updated policies. This should be sequenced after Issue #8 (Policy Framework) is completed to avoid re-doing the work.

**Policy linkage:** Global Information Security Policy · Regional Compliance Framework · Subsidiary Governance Policy
**Suggested Deadline:** **September 30, 2026** *(blocked until Issue #8 policy framework is finalized — sequence accordingly)*

---

## Deadline & Priority Summary

| Wave | Issues | Target Deadline | Rationale |
|---|---|---|---|
| **Already set** | #1, #2 | Mar 31, 2026 | Governance reporting deadlines |
| **Wave 1 — Critical / SOX** | #3, #8, #10, #11 | **Jun 30, 2026** | High severity + formal RCM Issues #1–#4; SOX 404 impact |
| **Wave 2 — Medium / Operational** | #4, #5, #6, #7, #9 | **Jun 30, 2026** | Medium severity; foundational for Wave 3 |
| **Wave 3 — Dependent / Complex** | #12, #13 | **Sep 30, 2026** | Requires lead time (network standards, BR/AR alignment after #8) |

> **Top priority action:** Set deadlines in Vanta for Issues **#3, #8, #10, #11** immediately — these carry the 4 formal High-priority RCM findings with no due date.

---

## Owner Summary

| Owner | Role | Vanta Issues |
|---|---|---|
| **David Cirielli (DC)** | CISO | #1, #2, #4, #7, #8, #9, #10, #11, #12, #13 |
| **OG** | IT Operations (see Vanta) | #3, #5, #6 |
| **Ezequiel Tavella** | Cybersecurity Manager | #12 (co-owner), #6 (FortiCloud co-owner) |

---

*Document generated: March 17, 2026*
*Branch: `claude/vanta-policies-mapping-xCgV7`*
