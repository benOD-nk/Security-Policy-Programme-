# Security Policy Programme: Status Summary

**Organisation:** Gallery Corp  
**Programme Owner:** Information Security Team  
**Reporting Period:** August 2026  
**Framework Alignment:** ISO/IEC 27001:2022, CIS Controls v8

---

## Programme Status

| Metric | Current Status |
|---|---|
| **Total policies in programme** | 4 (1 active, 3 planned) |
| **Policies due for review** | 0 |
| **Policies overdue for review** | 0 |
| **Open exceptions** | 1 (PAM implementation) |
| **Open audit gaps** | 3 |
| **Last governance review** | August 24, 2026 |

---

## Key Achievements This Period

- **POL-001 Access Control Policy** authored and cross-functional review completed.
- **STD-001 Access Control Standard** developed and aligned to applicable ISO/IEC 27001:2022 and CIS Controls v8 requirements.
- **Policy Register** established to track policy ownership, status, version, classification, framework references, and review dates.
- Policy and standard documentation is **version-controlled in GitHub** to support document governance and change tracking.
- **Access Control audit-readiness assessment** completed.
- Three access-control gaps were identified, documented, assigned risk levels, and added to the remediation plan.
- Cross-functional review comments from **IT Operations, HR, and Legal** were documented and resolved.
- PAM implementation was identified as an access-control capability gap and recorded for phased remediation.

---

## Open Gaps and Exceptions

| ID | Type | Description | Risk Level | Owner | Target Date | Status |
|---|---|---|---|---|---|---|
| **G001** | Audit Gap | No access review records available to demonstrate periodic validation of user access | High | Information Security / IT Operations | September 24, 2026 | Open |
| **G002** | Audit Gap | Joiner/Mover/Leaver procedure has not yet been formally documented and approved | Medium | HR / IT Operations | November 24, 2026 | Open |
| **G003** | Audit Gap | Formal access-control exception register has not yet been established | Medium | Information Security Team | September 24, 2026 | Open |
| **E001** | Exception | PAM capability required for separate administrative accounts is not currently available | Medium | Information Security / IT Operations | February 24, 2027 | Open |

---

## Priorities for Next Period

1. Complete and approve **PROC-001 Joiner/Mover/Leaver Procedure**.
2. Establish the **Access Control Exception Register** and formal exception-management process.
3. Conduct the first formal **user access review** and retain supporting evidence.
4. Track and remediate the **PAM implementation exception**.
5. Begin drafting **POL-002 Acceptable Use Policy**.
6. Update the audit-readiness checklist as remediation evidence becomes available.
7. Conduct a follow-up review of the identified access-control gaps.

---

## Governance Assessment

**Overall Programme Status:** 🟡 **Amber — In Progress**

Gallery Corp has established the foundational governance documentation for its security policy programme. POL-001, STD-001, the policy register, and the initial audit-readiness assessment are in place.

The programme remains **in progress** because operational evidence and supporting procedures for access reviews, Joiner/Mover/Leaver management, and exception management have not yet been fully established.

The immediate focus is to convert the documented policy requirements into **repeatable, evidenced operational processes** that can be demonstrated during an internal or external audit.

---

## Evidence Repository

| Evidence | GitHub Location |
|---|---|
| Access Control Policy | `/policies/access-control-policy.md` |
| Access Control Standard | `/standards/access-control-standard.md` |
| Policy Register | `/programme-management/policy-register.csv` |
| POL-001 Review Cycle | `/programme-management/pol-001-review-cycle.md` |
| Audit Readiness Checklist | `/audit/access-control-audit-readiness.md` |
| JML Procedure | `/procedures/joiner-mover-leaver.md` *(Planned)* |
| Exception Register | `/programme-management/access-control-exceptions.csv` *(Planned)* |
| Access Review Evidence | `/evidence/access-reviews/` *(Planned)* |
