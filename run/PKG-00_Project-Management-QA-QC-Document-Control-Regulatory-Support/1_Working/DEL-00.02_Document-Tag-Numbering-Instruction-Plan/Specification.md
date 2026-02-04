# Specification: DEL-00.02 Document & Tag Numbering Instruction Plan

**Document ID:** DEL-00.02-SP
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** Draft - Pending Review

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for the Document & Tag Numbering Instruction Plan to be developed by the Engineering Contractor for the Puget Sound Optimization Project (PSO). The plan shall provide comprehensive instructions for requesting and managing document numbers and equipment/instrument tags in coordination with TM systems.

### 1.2 Applicability

This specification applies to:
- All documents produced by the Engineering Contractor
- All drawings across all disciplines
- All equipment tags for new and modified equipment
- All instrument tags for new and modified instrumentation
- All piping line numbers

### 1.3 Boundaries

**In Scope:**
- Document numbering conventions and processes
- Drawing numbering conventions and processes
- Equipment tag numbering conventions and processes
- Instrument tag numbering conventions and processes
- Line numbering conventions
- Number request and allocation process with TM

**Out of Scope:**
- TM internal numbering systems (reference only)
- Historical numbering for existing assets (reference for consistency)

---

## 2. Requirements

### 2.1 Document Numbering Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| NUM-D-001 | Plan shall define document numbering structure per TM conventions | Mandatory | SOW-0441 |
| NUM-D-002 | Document numbers shall be unique within the project | Mandatory | SOW-0441 |
| NUM-D-003 | Plan shall define process for requesting document numbers from TM | Mandatory | SOW-0441 |
| NUM-D-004 | Document numbering shall support EDMS metadata requirements | Mandatory | SOW-0442 |
| NUM-D-005 | Plan shall address revision numbering conventions | Mandatory | SOW-0430 |
| NUM-D-006 | Plan shall address TM EDMS integration requirements | Mandatory | SOW-0442 |

### 2.2 Equipment Tag Numbering Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| NUM-E-001 | Plan shall define equipment tag structure per TM conventions | Mandatory | SOW-0441 |
| NUM-E-002 | Equipment tags shall be unique and not conflict with existing site tags | Mandatory | **ASSUMPTION** |
| NUM-E-003 | Plan shall define process for requesting equipment tags from TM | Mandatory | SOW-0441 |
| NUM-E-004 | Equipment tags shall support TM asset database requirements | Mandatory | **ASSUMPTION** |
| NUM-E-005 | Equipment tag structure shall identify equipment type and location | **ASSUMPTION** | Industry Practice |
| NUM-E-006 | Plan shall address TM asset database integration requirements | Mandatory | SOW-0442 |

### 2.3 Instrument Tag Numbering Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| NUM-I-001 | Plan shall define instrument tag structure per TM conventions | Mandatory | SOW-0441 |
| NUM-I-002 | Instrument tags shall follow ISA-5.1 or TM-specified convention | **ASSUMPTION** | Industry Practice |
| NUM-I-003 | Plan shall define process for requesting instrument tags from TM | Mandatory | SOW-0441 |
| NUM-I-004 | Instrument tags shall be compatible with control system requirements | Mandatory | SOW-0330 |

### 2.4 Line Numbering Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| NUM-L-001 | Plan shall define line numbering structure per TM conventions | Mandatory | SOW-0441 |
| NUM-L-002 | Line numbers shall identify service, size, material class, and sequence | **ASSUMPTION** | Industry Practice |
| NUM-L-003 | Line numbering shall be consistent with P&ID and LDT conventions | Mandatory | SOW-0250 |

### 2.5 Process Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| NUM-P-001 | Plan shall define roles and responsibilities for number management | Mandatory | SOW-0430 |
| NUM-P-002 | Plan shall define lead times for number requests | **ASSUMPTION** | Best Practice |
| NUM-P-003 | Plan shall define conflict resolution process | **ASSUMPTION** | Best Practice |

---

## 3. Standards

### 3.1 Applicable Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TM Standards and Specifications | TM corporate standards | Numbering conventions (**TBD** - Attachment A08) |
| ISA-5.1 | Instrumentation Symbols and Identification | Instrument tagging (**ASSUMPTION**) |
| TM EDMS Requirements | Electronic document management system requirements | Document numbering (**TBD**) |

### 3.2 Codes and Regulations

- No specific codes or regulations apply directly to numbering conventions
- Numbering shall support traceability for regulatory compliance documentation

### 3.3 TM-Specific Requirements

- Document numbering per TM conventions (SOW Section 4.3)
- Tag numbering consistent with existing Sumas Terminal assets
- Coordination with TM Document Control for number allocation

---

## 4. Verification

### 4.1 Verification Methods

| Req ID | Method | Acceptance Criteria |
|--------|--------|---------------------|
| NUM-D-001 | Review | TM approval of numbering structure |
| NUM-D-002 | Inspection | No duplicate document numbers in project |
| NUM-D-005 | Review | Revision numbering addressed in plan |
| NUM-D-006 | Review | EDMS integration requirements addressed |
| NUM-E-002 | Inspection | No conflicts with existing site tags |
| NUM-E-006 | Review | Asset database integration requirements addressed |
| NUM-I-002 | Review | Compliance with ISA-5.1 or TM standard |
| NUM-I-004 | Review | Control system compatibility verified |
| NUM-L-003 | Review | Consistency with P&ID and LDT conventions |
| NUM-P-001 | Review | Clear roles defined and assigned |

### 4.2 Review and Approval

| Milestone | Review Activity | Approver |
|-----------|-----------------|----------|
| Internal Review | Review by engineering leads and document control | Contractor Document Control Lead |
| Draft Submission | Review of conventions | TM Document Control |
| Final Approval | Approval for use | TM Project Team |
| Updates | Review of changes | TM Document Control |

### 4.3 Quality Checks

- Verify alignment with TM-provided conventions
- Confirm no conflicts with existing asset tags
- Validate EDMS compatibility

---

## 5. Documentation

### 5.1 Deliverables

| Document | Format | Timing |
|----------|--------|--------|
| Document & Tag Numbering Instruction Plan | .docx / .pdf | Project start |
| Revisions (as required) | .docx / .pdf | As needed |

### 5.2 Records

- TM approval records
- Number allocation logs
- Conflict resolution records

### 5.3 Retention

- Plan retained per TM document retention requirements (**TBD**)
- Native files archived with project documentation

---

## 6. Notes and Assumptions

1. **ASSUMPTION:** TM will provide baseline numbering conventions.
2. **ASSUMPTION:** ISA-5.1 applies for instrument tagging unless TM specifies otherwise.
3. **ASSUMPTION:** Equipment tag structure follows typical oilfield conventions (type-area-sequence).
4. **TBD:** Specific TM numbering conventions not yet available.
5. **TBD:** TM EDMS integration requirements not yet defined.

---

*Generated: Pass 2 - Cross-Reference Consistency Check*
*Source: PSO Decomposition REVISED v2, SOW Section 4.3*
*Updates: Added NUM-D-006, NUM-E-006 requirements; expanded verification table; added internal review milestone; corrected TMP→TM*
