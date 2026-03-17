# Vanta Issues ↔ RCM Audit Report — Policy Mapping

**Date:** March 17, 2026
**Scope:** IT Cybersecurity Audit 2026 — Kavak
**Source documents:**
- Vanta Issues (screenshot: `Issues Vanta.png`) — 8 open issues, all **Not Started**
- RCM Audit Report: `Copia COMPARTIDA de IT Cyber - RCM - 2026.xlsx` (sheets: `IT - RCM` & `Cyber - DE`)

---

## Summary Table

| # | Vanta Issue | Severity | RCM Control(s) | RCM Issue # | RCM Priority | Suggested Owner | Suggested Deadline |
|---|---|---|---|---|---|---|---|
| 1 | Annual Cybersecurity Strategy has not been reviewed or approved | Low | C.Cyber.Gov.01 | — | — | David Cirielli, CISO | **Mar 31, 2026** ✅ |
| 2 | Lack of updates and Reporting of the Cybersecurity Strategy to Cybersecurity Committees and the Board | Low | C.Cyber.Gov.02 | — | — | David Cirielli, CISO | **Mar 31, 2026** ✅ |
| 3 | Excessive system access (incl. BL) to the AD primary connectivity group | High | C.Cyber.CVN.05 / C.Cyber.NTW.06 | — | High | David Cirielli, CISO / Ezequiel Tavella, Cybersecurity Manager | **Apr 17, 2026** ✅ |
| 4 | Incomplete and Inaccurate Asset Inventory of Cybersecurity activity | Medium | C.Cyber.CVM.03 · C.Cyber.CVN.04 | **#3, #4** | High | David Cirielli, CISO | **Jun 30, 2026** ⬅ suggested |
| 5 | Incomplete Backup and Insufficient Data Retention Periods | Medium | C.Cyber.NTW.05 (FortiCloud) · C.Cyber.EUC.04 | — | Medium | David Cirielli, CISO | **Jun 30, 2026** ⬅ suggested |
| 6 | Inadequate documentation of policies, procedures and Standards | Medium | C.Cyber.Gov.03 · C.Cyber.RM.02 · C.Cyber.RM.03 · C.Cyber.NTW.01 | **#1** | High | David Cirielli, CISO | **Jun 30, 2026** ⬅ suggested |
| 7 | Lack of Formal Stakeholder Engagement and Accountability in Cybersecurity Risk Management | Medium | C.Cyber.Gov.05 · C.Cyber.RM.01 · C.Cyber.RM.04 | — | — | David Cirielli, CISO | **Jun 30, 2026** ⬅ suggested |
| 8 | Lack of Traceability of Endpoint Security Incidents / Network Security Control Gaps | Medium | C.Cyber.EUC.03 · C.Cyber.NTW.3.1 · C.Cyber.NTW.3.4 | **#2** | High | David Cirielli, CISO / Ezequiel Tavella, Cybersecurity Manager | **Sep 30, 2026** ⬅ suggested |

> ✅ = Deadline already set in Vanta
> ⬅ = Deadline suggested based on severity and SOX compliance calendar

---

## Detailed Mapping

---

### Vanta Issue #1 — Annual Cybersecurity Strategy not reviewed or approved
**Severity:** Low | **Vanta Status:** Not Started | **Due:** Mar 31, 2026

**RCM Control:** `C.Cyber.Gov.01` — Governance / 1.1 Strategy & Objective
**Audit Finding (Cyber-DE Row 2, Passed: N):**
> While the 2026 Cybersecurity Strategic Plan has been developed by the CISO, it has **not been formally reviewed or approved by the Board of Directors**. Additionally, the strategy is based on a 2025 Risk Appetite Statement that was informally agreed with prior executive management and has not been formally validated or updated to reflect current governance and risk context.

**Recommendation:** Formalize a documented, multi-year cybersecurity strategy aligned with NIST CSF 2.0, reviewed and approved by the Board. Update the Risk Appetite Statement accordingly.

**Policy linkage:** Cybersecurity Strategy Policy; Governance Framework
**Suggested Owner:** **David Cirielli, CISO**
**Suggested Deadline:** March 31, 2026 (already in Vanta — confirm progress)

---

### Vanta Issue #2 — Lack of updates and Reporting to Cybersecurity Committees and the Board
**Severity:** Low | **Vanta Status:** Not Started | **Due:** Mar 31, 2026

**RCM Control:** `C.Cyber.Gov.02` — Governance / 1.1 Strategy & Objective
**Audit Finding (Cyber-DE Row 3, Passed: N):**
> While there are monthly cybersecurity presentations to the CTO, the Cybersecurity Strategic Plan has **not yet been updated**, and compliance issues have **not been reported** to the Cybersecurity Committee, the Non-Financial Risk Committee, or the Audit Committee. Reporting mechanisms to the Board and governance committees are absent or incomplete.

**Recommendation:** Implement formal reporting cadence (at minimum quarterly) to the Cybersecurity Committee, Non-Financial Risk Committee, and Audit Committee. Formalize update process for the Strategic Plan.

**Policy linkage:** Cybersecurity Governance Policy; Reporting and Escalation Procedures
**Suggested Owner:** **David Cirielli, CISO**
**Suggested Deadline:** March 31, 2026 (already in Vanta — confirm progress)

---

### Vanta Issue #3 — Excessive system access (incl. BL) to AD primary connectivity group
**Severity:** High | **Vanta Status:** Not Started | **Due:** Apr 17, 2026

**RCM Controls:**
- `C.Cyber.CVN.05` — CVM / Access Management (marked N/A — to be reviewed under Network & Infrastructure audit)
- `C.Cyber.NTW.06` — Network / Network Communication Controls (access restrictions, segmentation, VPN/ZTNA)

**Audit Finding context:** This issue relates to excessive privileged access to Active Directory (AD) connectivity groups, including bulk/broad access listings (BL). While the Cyber-DE sheet marks network access controls as N/A (pending a full Network & Infrastructure review), the IT-RCM identifies access management as in-scope under `C.Cyber.NTW.06` (network access restrictions) and `C.Cyber.CVN.05` (endpoint access management). The AD over-provisioning gap also has connections to the finding on incomplete role and responsibilities definitions (`C.Cyber.Gov.04`):
> "Only the responsibilities of the CISO and the work teams are defined, not those of key positions" — making it difficult to enforce least-privilege access principles.

**Recommendation:** Conduct an immediate access review of all AD groups with broad/bulk memberships. Implement a recertification cycle for privileged groups. Define and enforce least-privilege access aligned with documented role requirements.

**Policy linkage:** Access Management Policy; Identity & Privilege Management Procedures; Network Security Standards
**Suggested Owner:** **David Cirielli, CISO / Ezequiel Tavella, Cybersecurity Manager**
**Suggested Deadline:** April 17, 2026 (already in Vanta — priority action given High severity)

---

### Vanta Issue #4 — Incomplete and Inaccurate Asset Inventory of Cybersecurity Activity
**Severity:** Medium | **Vanta Status:** Not Started | **Due:** *(not set in Vanta)*

**RCM Controls (Formal Issues):**
- `C.Cyber.CVM.03` — **RCM Issue #3** (High) — CVM / 3.3 Monitoring & Reporting
- `C.Cyber.CVN.04` — **RCM Issue #4** (High) — CVM / 3.4 Lifecycle Management

**Audit Finding (Cyber-DE Row 17, Passed: N) — Issue #3:**
> The Cybersecurity function does **not maintain a complete, accurate, and centrally governed inventory of information assets**, including cloud environments. Deficiencies identified in: asset inventory completeness, cloud security governance, penetration testing coverage, risk acceptance framework, and monitoring metrics.

**Audit Finding (Cyber-DE Row 18, Passed: N) — Issue #4:**
> The Cybersecurity function does **not maintain a formally documented and centrally governed inventory of cybersecurity tools**, including defined ownership, administrators, scope of coverage, and integration points for monitoring, vulnerability management, and incident response. The tool inventory was reconstructed through independent review of assessments, confirming the absence of a consolidated register.

**Recommendation:** Establish and maintain a centrally governed, periodically reconciled inventory of all information assets (including cloud/SOX-relevant systems) and all cybersecurity tools, with clearly assigned ownership, administrators, and integration points. Assign accountability to a permanent function (not a single individual).

**Policy linkage:** Asset Management Policy; Cloud Security Policy; Vulnerability Management Policy; Cybersecurity Tool Governance
**Suggested Owner:** **David Cirielli, CISO** (+ Ezequiel Tavella, Cybersecurity Manager for tooling)
**Suggested Deadline:** **June 30, 2026** *(aligns with H1 2026 SOX remediation window for High-priority issues)*

---

### Vanta Issue #5 — Incomplete Backup and Insufficient Data Retention Periods
**Severity:** Medium | **Vanta Status:** Not Started | **Due:** *(not set in Vanta)*

**RCM Controls:**
- `C.Cyber.NTW.05` — Network / 4.4 Lifecycle Management (FortiCloud Log Management)
- `C.Cyber.EUC.04` — Endpoint Security / Lifecycle Management (endpoint data controls)

**Audit Finding (Cyber-DE Row 29, Passed: N):**
> **Lack of Automated Patching and Monitoring Controls for FortiCloud Log Management Environment.** Review identified deficiencies related to: currency of security patches (outdated FortiCloud version), inadequate operational monitoring of log completeness and availability, and absence of automated alerting for patch status or service disruptions.
>
> This directly impacts the integrity and availability of log data used for forensic, compliance, and audit purposes — including SOX evidence retention.

**Recommendation:** Implement automated patch management for the FortiCloud environment. Establish formal data retention schedules aligned with SOX requirements (minimum 7 years for financial system logs). Set up monitoring alerts for log availability gaps and patch currency.

**Policy linkage:** Backup and Recovery Policy; Data Retention Policy; Log Management Procedures; FortiCloud Operating Standards
**Suggested Owner:** **David Cirielli, CISO**
**Suggested Deadline:** **June 30, 2026** *(Medium priority; critical for SOX log integrity)*

---

### Vanta Issue #6 — Inadequate Documentation of Policies, Procedures and Standards
**Severity:** Medium | **Vanta Status:** Not Started | **Due:** *(not set in Vanta)*

**RCM Controls (Multiple):**
- `C.Cyber.Gov.03` — Governance / 1.2 Policies and Procedures
- `C.Cyber.RM.02` — Risk Management / 2.2 Risk Management (policy approval gaps)
- `C.Cyber.RM.03` — Risk Management / 2.3 Accountability & Responsibility
- `C.Cyber.NTW.01` — Network / 4.1 Internal Controls (missing network security standards)
- `C.Cyber.CVM.01` — **RCM Issue #1** (High) — CVM / 2.6 Incident Response and Recovery

**Audit Findings:**

*C.Cyber.Gov.03 (DE Row 4, Passed: N):*
> "Not all cybersecurity documents are formally approved; they are under review prior to final approval. Official documents are **not available in English or local languages**. Some policies are approved only by the Cybersecurity Manager (not the CISO). Coverage gaps exist across encryption, endpoint security, and other domains."

*C.Cyber.RM.02 (DE Row 9, Passed: N):*
> "Management has **not formally approved (CISO) or consistently applied** cybersecurity policies, risk management processes, and awareness controls. Policies are approved only by the Cybersecurity Manager and are at various stages of drafting, review, or partial approval."

*C.Cyber.CVM.01 / RCM Issue #1 (DE Row 13, Passed: N):*
> "The Company has **not established or fully implemented a comprehensive, formally approved Cybersecurity Policy framework**. Policies, standards, and procedures remain incomplete, inconsistently approved, and not formally communicated across the organization."

*C.Cyber.NTW.01 (DE Row 23, Passed: N):*
> "No formal standards were identified for VPN solutions (Netskope and Pritunl), Fortinet firewalls, IPS configurations, or VLAN segmentation rules. Configuration baselines are not documented."

**Recommendation:** Establish a comprehensive, CISO-approved cybersecurity policy framework covering all domains. Publish policies in all required languages. Assign formal document owners and define an annual review and approval cycle. Network security standards (VPN, firewall, IPS) must be formally documented and approved.

**Policy linkage:** Information Security Policy; Cybersecurity Policy Framework; Acceptable Use Policy; Network Security Standards; Encryption Standards; Endpoint Security Policy
**Suggested Owner:** **David Cirielli, CISO**
**Suggested Deadline:** **June 30, 2026** *(High priority — directly impacts SOX 404 compliance and RCM Issue #1)*

---

### Vanta Issue #7 — Lack of Formal Stakeholder Engagement and Accountability in Cybersecurity Risk Management
**Severity:** Medium | **Vanta Status:** Not Started | **Due:** *(not set in Vanta)*

**RCM Controls:**
- `C.Cyber.Gov.05` — Governance / 1.4 Stakeholder Engagement
- `C.Cyber.RM.01` — Risk Management / 2.1 Risk Assessment
- `C.Cyber.RM.04` — Risk Management / 2.4 Escalation of Risks
- `C.Cyber.RM.05` — Risk Management / 2.5 Timely Communication & Reporting

**Audit Findings:**

*C.Cyber.Gov.05 (DE Row 6, Passed: N):*
> "A review of the risk register and related reporting (Sep 2025 – Jan 2026) identified that **approximately 75% of risks associated with third parties remain pending escalation or formal treatment decisions**. Stakeholder ownership and escalation paths for identified cybersecurity risks are not consistently enforced."

*C.Cyber.RM.01 (DE Row 8, Passed: N):*
> "The Company **has not established a formal, documented cybersecurity risk assessment process** fully integrated with the Enterprise Risk Management (ERM) framework. No comprehensive periodic risk assessment evidenced. Risk appetite elements exist in the 2026 strategy but are not operationalized in a structured process."

*C.Cyber.RM.04/05 (DE Rows 11-12, Passed: N):*
> Both refer to the same gap as C.Cyber.RM.02 — absence of formal escalation and timely reporting mechanisms for cybersecurity risks.

**Recommendation:** Define and implement a formal cybersecurity risk management process integrated with ERM. Establish documented RACI for risk ownership, escalation triggers, and reporting timelines to governance bodies. Remediate the backlog of third-party risks pending treatment decision.

**Policy linkage:** Cybersecurity Risk Management Policy; Third-Party Risk Management Policy; Risk Escalation Procedures; ERM Integration Framework
**Suggested Owner:** **David Cirielli, CISO**
**Suggested Deadline:** **June 30, 2026**

---

### Vanta Issue #8 — Network Security Control Gaps / Lack of Traceability of Endpoint Security Incidents
**Severity:** Medium | **Vanta Status:** Not Started | **Due:** *(not set in Vanta)*

**RCM Controls (Formal Issue):**
- `C.Cyber.CVM.02` — **RCM Issue #2** (High) — CVM / Training & Awareness (key-person dependency)
- `C.Cyber.NTW.3.1` / `C.Cyber.NTW.3.4` — Network / Change Management, Logging & Review
- `C.Cyber.EUC.03` — Endpoint Security / Monitoring & Reporting (Cortex traceability)
- `C.Cyber.NTW.07` — Network / 4.7 Network Communication Controls (Brazil & Argentina policy misalignment)

**Audit Findings:**

*C.Cyber.CVM.02 / RCM Issue #2 (High):*
> CVM function is **dependent on a single key individual (Cyber Principal)** with no formal backup or alternate. No dedicated CVM team structure or formal skill/certification requirements established. Key-person dependency creates operational and SOX control risk.

*C.Cyber.NTW.3.1 / NTW.3.4 (DE Row 25, Passed: N):*
> "Weaknesses in Network Security Change Management, Logging, and Periodic Review Controls. Fortinet firewall configuration changes are **not consistently authorized, documented, or reviewed**. Log monitoring gaps and absence of periodic security configuration reviews identified."

*C.Cyber.EUC.03 / NTW.07 (DE Row 30, Passed: N):*
> "**Security incidents detected on endpoints through the Cortex platform are not consistently recorded or traceable** within the organization's formal incident management system. Alerts cannot be systematically reconciled with tickets, creating an audit trail gap."

*C.Cyber.NTW.07 (DE Row 32, Passed: N):*
> "**Misalignment Between Cybersecurity Policies and Current Governance Framework — Brazil and Argentina.** Policies communicated to employees in BR and AR do not reflect current cybersecurity standards or KAVAK's information security governance framework."

**Recommendation:**
(i) Establish a formal CVM team structure, eliminating key-person dependency (RCM Issue #2).
(ii) Implement a formal network change management process for Fortinet firewalls with documented authorization, change logs, and periodic reviews.
(iii) Integrate Cortex endpoint alerts with the formal incident management system to ensure full traceability.
(iv) Align cybersecurity policies in Brazil and Argentina with the global governance framework.

**Policy linkage:** Incident Management Policy; Change Management Policy; Network Security Standards; Endpoint Security Policy; Regional Policy Compliance (Brazil/Argentina)
**Suggested Owner:** **David Cirielli, CISO / Ezequiel Tavella, Cybersecurity Manager**
**Suggested Deadline:** **September 30, 2026** *(includes CVM team build-out — requires more lead time; RCM Issue #2 High priority should be escalated if no progress by Jun 30)*

---

## Deadline Summary

| Priority | # Vanta Issues | Suggested Deadline | Key Owners |
|---|---|---|---|
| Already set | 1, 2 | **Mar 31, 2026** | David Cirielli, CISO |
| Already set (High) | 3 | **Apr 17, 2026** | David Cirielli / Ezequiel Tavella |
| Suggested — H1 SOX window | 4, 5, 6, 7 | **Jun 30, 2026** | David Cirielli, CISO |
| Suggested — H2 remediation | 8 | **Sep 30, 2026** | David Cirielli / Ezequiel Tavella |

> **Note:** Issues 4, 6 carry formal **RCM Issues #1, #3, #4 (High priority)**. If no deadline is set in Vanta for these, they should be added immediately given their SOX 404 impact.

---

## RCM Formal Issues Cross-Reference

| RCM Issue # | RCM Control | Priority | Description | Linked Vanta Issue |
|---|---|---|---|---|
| **#1** | C.Cyber.CVM.01 | High | No comprehensive, formally approved Cybersecurity Policy framework | **Vanta #6** |
| **#2** | C.Cyber.CVM.02 | High | Key-person dependency in CVM function; no formal team structure | **Vanta #8** |
| **#3** | C.Cyber.CVM.03 | High | Incomplete asset inventory; cloud security governance gaps; no pen testing coverage | **Vanta #4** |
| **#4** | C.Cyber.CVN.04 | High | No centralized cybersecurity tool inventory; lifecycle management gaps | **Vanta #4** |

---

## Owner Summary

| Owner | Vanta Issues |
|---|---|
| **David Cirielli, CISO** | #1, #2, #3, #4, #5, #6, #7, #8 (primary on all) |
| **Ezequiel Tavella, Cybersecurity Manager** | #3, #8 (co-owner for network/endpoint areas) |

---

*Document generated: March 17, 2026*
*Branch: `claude/vanta-policies-mapping-xCgV7`*
