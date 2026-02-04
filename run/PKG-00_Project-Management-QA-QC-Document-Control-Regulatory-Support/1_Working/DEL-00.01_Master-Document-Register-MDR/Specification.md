# Specification: DEL-00.01 Master Document Register (MDR)

**Document ID:** DEL-00.01-SP
**Revision:** Pass 2 (Consistency Check)
**Date:** 2026-02-01
**Status:** Draft - Consistency Checked

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for the Master Document Register (MDR) to be developed and maintained by the Engineering Contractor for the Puget Sound Optimization Project (PSO). The MDR shall serve as the comprehensive register of all documents, drawings, and reports produced as part of the engineering work.

### 1.2 Applicability

This specification applies to:
- All FEED and Detailed Design deliverables across all disciplines (PKG-00 through PKG-09)
- All document types including drawings, calculations, reports, specifications, data sheets, lists, and registers
- Both internal contractor documents and documents submitted to TM

### 1.3 Boundaries

**In Scope:**
- All Engineering Contractor-produced documents
- Revision history tracking
- Document status management
- Transmittal reference tracking

**Out of Scope:**
- TM-owned documents (reference only)
- Vendor documents (tracked separately per discipline requirements)
- Third-party documents

---

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| MDR-F-001 | MDR shall list all documents, drawings, and reports produced for the PSO project | Mandatory | SOW-0208 |
| MDR-F-002 | MDR shall be maintained in a format compatible with TM EDMS | Mandatory | SOW-0441 |
| MDR-F-003 | MDR shall track document revisions and status changes | Mandatory | SOW-0430 |
| MDR-F-004 | MDR shall support cross-referencing with TM document control systems | Mandatory | SOW-0442 |
| MDR-F-005 | MDR shall be updated for each document submission | Mandatory | SOW-0442 |

### 2.2 Content Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| MDR-C-001 | Each entry shall include unique document number per TM conventions | Mandatory | SOW-0441 |
| MDR-C-002 | Each entry shall include document title, type, and discipline | Mandatory | **ASSUMPTION** |
| MDR-C-003 | Each entry shall include current revision and issue date | Mandatory | **ASSUMPTION** |
| MDR-C-004 | Each entry shall include document status (DFT/IFR/IFD/IFC/AB) | Mandatory | SOW-0104 |
| MDR-C-005 | Each entry shall include responsible originator and approver | Mandatory | SOW-0420 |
| MDR-C-006 | Each entry shall include reviewer name | Mandatory | **ASSUMPTION** |
| MDR-C-007 | Each entry shall include TM EDMS reference | **TBD** | **ASSUMPTION** |
| MDR-C-008 | Each entry shall include transmittal reference | **TBD** | **ASSUMPTION** |

### 2.3 Format Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| MDR-FM-001 | MDR shall use TM-provided template (or TM-approved format) | Mandatory | SOW-0441 |
| MDR-FM-002 | MDR shall be provided in native Excel format (.xlsx) | Mandatory | SOW-0442 |
| MDR-FM-003 | MDR shall be provided as PDF for each formal submission | Mandatory | SOW-0442 |
| MDR-FM-004 | MDR shall support sorting and filtering on key fields | Recommended | Best Practice |

### 2.4 Submission Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| MDR-S-001 | MDR shall be submitted with each major deliverable package | Mandatory | SOW-0442 |
| MDR-S-002 | MDR shall be submitted at end of FEED (with IFD package) | Mandatory | SOW-0104 |
| MDR-S-003 | MDR shall be submitted at end of Detailed Design (with IFC package) | Mandatory | SOW-0209 |
| MDR-S-004 | Final MDR shall be included in Final Documentation Package | Mandatory | SOW-0209 |

---

## 3. Standards

### 3.1 Applicable Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TMP Standards and Specifications | TM corporate standards | Document control requirements (**TBD** - Attachment A08) |
| TM EDMS Requirements | Electronic document management system requirements | Compatibility and metadata (**TBD**) |

### 3.2 Codes and Regulations

- No specific codes or regulations apply directly to the MDR format
- MDR shall support traceability for regulatory compliance documentation

### 3.3 TM-Specific Requirements

- Document numbering per TM conventions (ref: DEL-00.02)
- Metadata compatibility with TM EDMS (**TBD**)
- File naming conventions per SOW Section 4.3

---

## 4. Verification

### 4.1 Verification Methods

| Req ID | Method | Acceptance Criteria |
|--------|--------|---------------------|
| MDR-F-001 | Inspection | All deliverables listed; no omissions |
| MDR-F-002 | Demonstration | Successful import to TM EDMS |
| MDR-F-003 | Inspection | Revision history complete and accurate |
| MDR-F-004 | Demonstration | Cross-reference fields populated correctly |
| MDR-F-005 | Audit | Update log shows entries for each submission |

### 4.2 Review and Approval

| Milestone | Review Activity | Approver |
|-----------|-----------------|----------|
| Initial Setup | Template and structure review | TM Document Control |
| End of FEED | IFD MDR review | TM Project Team |
| End of DD | IFC MDR review | TM Project Team |
| Final | FD Package MDR verification | TM Document Control |

### 4.3 Quality Checks

- Cross-check MDR against transmittal logs
- Verify document numbers against TM numbering system
- Confirm all issued documents are captured
- Validate revision levels match issued documents

---

## 5. Documentation

### 5.1 Deliverables

| Document | Format | Timing |
|----------|--------|--------|
| MDR (Excel native) | .xlsx | Each submission |
| MDR (PDF export) | .pdf | Each submission |
| MDR Revision History | Embedded in MDR | Continuous |

### 5.2 Records

- Transmittal records for MDR submissions
- TM review comments and responses
- Change log for MDR updates

### 5.3 Retention

- All MDR revisions retained for project duration plus **TBD** years per TM document retention requirements
- Native files archived with final documentation package

---

## 6. Notes and Assumptions

1. **ASSUMPTION:** TM will provide an MDR template or approve contractor-proposed format.
2. **ASSUMPTION:** Standard spreadsheet fields are assumed based on industry practice.
3. **TBD:** TM EDMS metadata field requirements not yet defined.
4. **TBD:** Specific submission frequency to be confirmed with TM.
5. **ASSUMPTION:** Excel format is acceptable; alternative formats may be required per TM direction.

---

*Generated: Pass 1 - Initial Draft, Pass 2 - Consistency Check*
*Source: PSO Decomposition REVISED v2, SOW Sections 3.2.2.7, 4.2.5, 4.3*
