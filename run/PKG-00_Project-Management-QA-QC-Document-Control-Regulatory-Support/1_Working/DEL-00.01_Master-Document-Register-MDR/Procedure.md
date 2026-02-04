# Procedure: DEL-00.01 Master Document Register (MDR)

**Document ID:** DEL-00.01-PR
**Revision:** Pass 2 (Consistency Check)
**Date:** 2026-02-01
**Status:** Draft - Consistency Checked

---

## 1. Purpose

### 1.1 Objective

This procedure defines the step-by-step process for creating, maintaining, and submitting the Master Document Register (MDR) for the Puget Sound Optimization Project (PSO).

### 1.2 Scope

This procedure covers:
- Initial MDR setup
- Document registration process
- Revision management
- Submission to TM
- Final closeout

---

## 2. Prerequisites

### 2.1 Required Inputs

| Input | Source | Status |
|-------|--------|--------|
| TM MDR Template (or format approval) | TM Document Control | **TBD** |
| Document Numbering Convention | TM / DEL-00.02 | **TBD** |
| TM EDMS Metadata Requirements | TM Document Control | **TBD** |
| Project Document List (preliminary) | Engineering Disciplines | Available |

### 2.2 Required Resources

| Resource | Description |
|----------|-------------|
| Document Controller | Designated MDR owner |
| Excel or approved software | For MDR creation and maintenance |
| Access to TM EDMS | For upload and cross-reference (**TBD**) |

### 2.3 Required Authorizations

| Authorization | Holder |
|---------------|--------|
| MDR Structure Approval | TM Document Control |
| Document Number Requests | Contractor Document Control via TM process |

---

## 3. Steps

### 3.1 Initial Setup

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1.1 | Obtain TM MDR template or confirm format requirements | Document Controller | Approved template/format |
| 3.1.2 | Review Document Numbering Instruction Plan (DEL-00.02) | Document Controller | Understanding of numbering conventions |
| 3.1.3 | Configure MDR structure with required fields | Document Controller | Blank MDR ready for population |
| 3.1.4 | Define status codes and revision conventions | Document Controller | Status code definitions |
| 3.1.5 | Submit MDR structure to TM for review/approval | Document Controller | TM approval |

### 3.2 Document Registration

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.2.1 | Receive document from originating discipline | Document Controller | Document file received |
| 3.2.2 | Verify document number compliance with convention | Document Controller | Verified number |
| 3.2.3 | Enter document details into MDR | Document Controller | New MDR entry |
| 3.2.4 | Assign status code (DFT, IFR, IFD, IFC, AB) | Document Controller | Status assigned |
| 3.2.5 | Link to transmittal reference (if applicable) | Document Controller | Transmittal cross-reference |
| 3.2.6 | Save updated MDR with revision history entry | Document Controller | Updated MDR |

### 3.3 Revision Management

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.3.1 | Receive revised document from discipline | Document Controller | Revised document file |
| 3.3.2 | Verify revision number follows convention | Document Controller | Verified revision |
| 3.3.3 | Update MDR entry with new revision information | Document Controller | Updated entry |
| 3.3.4 | Update status code if changed | Document Controller | Current status |
| 3.3.5 | Archive previous MDR version | Document Controller | Archived version |
| 3.3.6 | Log revision in MDR change log | Document Controller | Audit trail |

### 3.4 Submission to TM

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.4.1 | Prepare MDR export for submission | Document Controller | Native Excel file |
| 3.4.2 | Generate PDF export of MDR | Document Controller | PDF file |
| 3.4.3 | Perform QC check (see Section 4) | Document Controller | QC checklist complete |
| 3.4.4 | Include MDR in transmittal package | Document Controller | Transmittal with MDR |
| 3.4.5 | Upload to TM EDMS (if required) | Document Controller | EDMS confirmation |
| 3.4.6 | Log submission in transmittal register | Document Controller | Submission record |

### 3.5 Final Closeout

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.5.1 | Verify all project documents are captured | Document Controller | Completeness check |
| 3.5.2 | Confirm all documents have final status (IFC/As-Built) | Document Controller | Status verification |
| 3.5.3 | Prepare final MDR for FD Package | Document Controller | Final MDR |
| 3.5.4 | Obtain TM acceptance of final MDR | Document Controller | TM acceptance |
| 3.5.5 | Archive final MDR with project records | Document Controller | Archived record |

---

## 4. Verification

### 4.1 Quality Control Checklist

| Check Item | Verification Method | Pass Criteria |
|------------|---------------------|---------------|
| All transmittals reflected | Cross-reference transmittal log | 100% match |
| Document numbers valid | Validate against numbering convention | All valid |
| No duplicate entries | Sort and review | No duplicates |
| Status codes current | Compare to latest issued documents | All current |
| Revision levels correct | Compare to document files | All match |
| Required fields complete | Filter for blanks | No blank mandatory fields |
| Sorting and filtering functional | Test Excel filters on key columns | All columns sortable/filterable |

### 4.2 Review Requirements

| Milestone | Reviewer | Approval |
|-----------|----------|----------|
| Initial Setup | Document Control Lead | Internal |
| First Submission | TM Document Control | TM |
| IFD Submission | TM Project Team | TM |
| IFC Submission | TM Project Team | TM |
| Final MDR | TM Document Control | TM |

### 4.3 Issue Resolution

| Issue Type | Resolution Process |
|------------|---------------------|
| Missing document | Contact originating discipline; add immediately |
| Incorrect entry | Correct and log in revision history |
| TM rejection | Review comments; revise and resubmit |

---

## 5. Records

### 5.1 Generated Records

| Record | Format | Retention |
|--------|--------|-----------|
| MDR (all versions) | .xlsx | Project duration + **TBD** years |
| MDR (PDF exports) | .pdf | Project duration + **TBD** years |
| MDR Change Log | Embedded in MDR | Project duration + **TBD** years |
| QC Checklists | .pdf or electronic | Project duration + **TBD** years |
| TM Review Comments/Responses | .pdf or electronic | Project duration + **TBD** years |

### 5.2 Storage Location

- Native files: Contractor document management system
- Submitted files: TM EDMS (**TBD** - access and upload process)
- Archive: Per TM document retention requirements

### 5.3 Naming Convention

- **ASSUMPTION:** `[Project Number]-MDR-[Rev]-[Date].xlsx`
- Example: `2500-MDR-Rev3-20260401.xlsx`
- Confirm with TM naming convention requirements

---

## 6. Notes and Assumptions

1. **ASSUMPTION:** Procedure assumes Excel-based MDR; adjust if TM requires different format.
2. **ASSUMPTION:** Weekly update frequency assumed; confirm with TM.
3. **TBD:** TM EDMS upload process not yet defined.
4. **TBD:** Document retention period not specified.
5. **TBD:** Specific TM review/approval cycle times not defined.

---

## 7. Revision History

| Revision | Date | Description | Author |
|----------|------|-------------|--------|
| Pass 1 | 2026-02-01 | Initial draft - Pass 1 generation | PSO Team |
| Pass 2 | 2026-02-01 | Consistency check and corrections | PSO Team |

---

*Generated: Pass 1 - Initial Draft, Pass 2 - Consistency Check*
*Source: PSO Decomposition REVISED v2, SOW Sections 3.2.2.7, 4.2.5, 4.3*
