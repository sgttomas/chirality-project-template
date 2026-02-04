# Datasheet: DEL-00.04 Design Change Control Log (Pass 2 — Cross-Reference & Enriched)

**Document ID:** DEL-00.04-DS
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** Draft - Pending Review

---

## 1. Identification

| Attribute | Value |
|-----------|-------|
| **Deliverable ID** | DEL-00.04 |
| **Deliverable Name** | Design Change Control Log |
| **Parent Package** | PKG-00 Project Management, QA/QC, Document Control & Regulatory Support |
| **Discipline** | Project Controls |
| **Deliverable Type** | Register |
| **Responsible Party** | Engineering Contractor |
| **Project** | Puget Sound Optimization Project (PSO) |
| **Facility** | Sumas Tank Farm (Sumas Terminal) |

---

## 2. Attributes

### 2.1 Physical/Format Attributes

| Attribute | Value |
|-----------|-------|
| **Format** | Electronic spreadsheet (Excel) and PDF |
| **Template Source** | Contractor standard template, adapted for TM requirements |
| **Native File Format** | .xlsx (Microsoft Excel) |
| **PDF Export** | Required for formal submissions |
| **Version Control** | Continuous log; snapshot revisions for submissions |

### 2.2 Content Attributes

| Attribute | Value |
|-----------|-------|
| **Scope Coverage** | All design changes during FEED and Detailed Design |
| **Change Types** | Scope changes, design modifications, deviation requests, MOC items, corrections |
| **Phases Covered** | FEED and Detailed Design |
| **Integration** | Links to affected documents and approval records |

**Note:** Five change types are tracked (per Guidance Section 3.1): (1) Scope Change, (2) Design Modification, (3) Deviation, (4) MOC (Management of Change), (5) Correction (error correction without design impact).

### 2.3 Key Data Fields

| Field Name | Description | Mandatory | Pass 2 Cross-Reference |
|------------|-------------|-----------|------------------------|
| Change ID | Unique identifier for the change | Yes | Specification: CCL-C-001; Procedure: Step 3.2.3; Guidance: Example "DCN-2026-0015" |
| Change Title | Brief descriptive title | Yes | Specification: CCL-C-002 (description); Guidance: Section 5.1 example |
| Change Description | Detailed description of the change | Yes | Specification: CCL-C-002; Procedure: Step 3.2.5; Guidance: Section 5.1 example |
| Discipline | Originating discipline | Yes | Specification: CCL-C-003; Procedure: Step 3.2.1; Guidance: Example shows "Process" |
| Change Type | Classification (Scope/Design/Deviation/MOC) | Yes | Specification: CCL-C-004; Procedure: Step 3.2.4; Guidance: Section 3.1 (5 types) |
| Reason for Change | Justification or trigger for change | Yes | Specification: CCL-C-002; Procedure: Step 3.2.5; Guidance: Section 5.1 example |
| Affected Documents | List of documents impacted | Yes | Specification: CCL-C-005, CCL-F-003; Procedure: Step 3.2.6; Guidance: Section 3.3 |
| Cost Impact | Estimated cost impact (if any) | **TBD** - Field required; value may be "TBD" if not yet assessed | Procedure: Step 3.2.7 (impact assessment); Guidance: Example shows "TBD - Pending vendor update" |
| Schedule Impact | Estimated schedule impact (if any) | **TBD** - Field required; value may be "TBD" if not yet assessed | Procedure: Step 3.2.7 (impact assessment); Guidance: Example shows "None expected" |
| Originator | Person initiating the change | Yes | Specification: CCL-C-002; Procedure: Step 3.2.1-3.2.2; Guidance: Example "J. Smith" |
| Date Initiated | Date change was raised | Yes | Procedure: Step 3.2.2; Guidance: Example "2026-03-15" |
| Approval Status | Current approval status | Yes | Specification: CCL-F-002; Procedure: Step 3.3.7; Guidance: Section 5.1 example |
| Approver(s) | Names of required approvers | Yes | Specification: CCL-C-006; Procedure: Section 3.3; Guidance: Section 5.3 (approval workflow) |
| Approval Date | Date of approval (if approved) | Yes (when applicable) | Specification: CCL-C-006; Procedure: Step 3.3.7; Section 4.1 (verification) |
| Implementation Status | Status of implementation | Yes | Specification: CCL-C-007; Procedure: Section 3.4; Guidance: Principle "Closure Discipline" |
| Closure Date | Date change was closed | Yes (when applicable) | Specification: CCL-C-007; Procedure: Step 3.5.4; Section 5.1 (record retention) |
| Remarks | Additional notes | No | Implicit field for additional context |

---

## 3. Conditions

### 3.1 Prerequisites

- Change control procedure established
- Document numbering convention (DEL-00.02)
- MDR structure for linking affected documents (DEL-00.01)
- Approval authority definitions

### 3.2 Dependencies

| Dependency | Source | Status | Pass 2 Cross-Reference |
|------------|--------|--------|------------------------|
| Change Control Procedure | Contractor / TM | **TBD** | Procedure: Section 2.1 (Required Input); Specification: Section 3.1 (Contractor procedures) |
| Document Numbering | DEL-00.02 | Pending | Procedure: Section 2.1 (Required Input); Guidance: Section 3.3 (MDR Linkage) |
| MDR | DEL-00.01 | Pending | Specification: CCL-F-003 (cross-reference to MDR); Section 5.2 (Related Deliverables); Procedure: Step 3.4.3 |
| TM Approval Requirements | SOW | Available | Specification: CCL-P-002 (SOW-0205); Procedure: Section 2.3 (TM authorizations) |

### 3.3 Constraints

- All design changes must be logged before implementation
- Scope changes require TM approval
- Deviations from TM standards require TM approval
- Log must support audit and traceability

---

## 4. Construction / Compilation

### 4.1 Development Approach

| Phase | Activity |
|-------|----------|
| Setup | Create log structure with required fields |
| Initialization | Establish baseline with project start |
| Continuous | Log entries added as changes occur |
| Reporting | Periodic snapshots for progress reporting |
| Closeout | Final log included in project records |

### 4.2 Update Frequency

- Real-time entry as changes are raised
- Status updates as approvals progress
- **ASSUMPTION:** Weekly snapshot for progress reporting

### 4.3 Quality Control

- Verify all changes have unique IDs
- Confirm affected documents are identified
- Validate approval chain is complete before closure
- Cross-check against document revisions

---

## 5. References

### 5.1 Source Documents

| Reference | Document | Section |
|-----------|----------|---------|
| SOW-0420 | Exhibit A - Scope of Work PS.pdf | Section 4.2.4.1-4.2.4.7 |
| SOW-0205 | Exhibit A - Scope of Work PS.pdf | Section 3.2.2.3 |

### 5.2 Related Deliverables

| Deliverable ID | Name | Relationship | Pass 2 Cross-Reference |
|----------------|------|--------------|------------------------|
| DEL-00.01 | Master Document Register (MDR) | Links to affected documents | Specification: CCL-F-003 (verification against MDR); Procedure: Step 3.4.3 (Update MDR); Guidance: Section 3.3 |
| DEL-00.03 | Deliverable Review & Verification Plan | Changes may trigger reviews | Implicit relationship; changes requiring review logged here |
| DEL-01.14 | Specification Deviations (Process) | Related deviation tracking | Guidance: Section 3.1 (Deviation type) relates to discipline-specific deviation tracking |

### 5.3 Applicable Standards

- TMP Standards and Specifications (**TBD** - Attachment A08 not available)
- Contractor change control procedures (**ASSUMPTION**)

---

## 6. Notes and Assumptions

1. **ASSUMPTION:** Contractor has baseline change control procedures.
2. **ASSUMPTION:** Cost/schedule impact fields may be optional depending on TM requirements.
3. **TBD:** TM approval thresholds for change types not specified.
4. **TBD:** Integration with TM change management systems.
5. **TBD:** Reporting frequency for change log summaries.

---

## 7. Pass 2 Cross-Reference Summary

### 7.1 Internal Consistency

All data fields in Section 2.3 are traceable to:
- Specification requirements (Section 2.1-2.4)
- Procedure steps (Sections 3.1-3.6)
- Guidance examples and principles (Sections 2.1, 3.1, 5.1)

### 7.2 Key Dependencies Validated

- **DEL-00.01 (MDR)**: Referenced for affected document tracking (CCL-F-003)
- **DEL-00.02**: Referenced for document numbering convention
- **DEL-00.03**: Related to review triggers

### 7.3 TBD Items Carried Forward

1. **Cost/Schedule Impact Mandatory Status**: Marked as TBD in Section 2.3
2. **TM Approval Thresholds**: Noted as TBD in Sections 6 and throughout
3. **Change Control Procedure Source**: Marked as TBD in Section 3.2
4. **TM System Integration**: Noted as TBD in Section 6

---

*Generated: Pass 2 - Cross-Reference Consistency Check*
*Source: PSO Decomposition REVISED v2, DEL-00.04 Context*
