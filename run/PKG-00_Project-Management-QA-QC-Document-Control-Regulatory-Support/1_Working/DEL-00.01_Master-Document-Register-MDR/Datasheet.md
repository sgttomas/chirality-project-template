# Datasheet: DEL-00.01 Master Document Register (MDR)

**Document ID:** DEL-00.01-DS
**Revision:** Pass 2 (Consistency Check)
**Date:** 2026-02-01
**Status:** Draft - Consistency Checked

---

## 1. Identification

| Attribute | Value |
|-----------|-------|
| **Deliverable ID** | DEL-00.01 |
| **Deliverable Name** | Master Document Register (MDR) |
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
| **Template Source** | TM-provided template (**TBD** - template to be obtained from TM) |
| **Native File Format** | .xlsx (Microsoft Excel) |
| **PDF Export** | Required for each submission |
| **Version Control** | Sequential revision numbering (Rev 0, Rev 1, etc.) |

### 2.2 Content Attributes

| Attribute | Value |
|-----------|-------|
| **Scope Coverage** | All documents, drawings, and reports produced for PSO |
| **Document Categories** | Drawings, Specifications, Calculations, Reports, Plans, Data Sheets, Lists, Registers |
| **Phases Covered** | FEED and Detailed Design |
| **Revision Tracking** | All revisions to be logged with dates and reasons |
| **Status Codes** | Draft (DFT), Issued for Review (IFR), Issued for Design (IFD), Issued for Construction (IFC), As-Built (AB) |
| **Revision Convention** | Numeric (0, 1, 2...) for issued documents; Alpha (A, B, C...) for review drafts (**ASSUMPTION**) |

### 2.3 Key Data Fields

| Field Name | Description | Mandatory |
|------------|-------------|-----------|
| Document Number | Unique identifier per TM numbering convention | Yes |
| Document Title | Full descriptive title | Yes |
| Document Type | Category (Drawing, Report, etc.) | Yes |
| Discipline | Engineering discipline owner | Yes |
| Revision | Current revision level | Yes |
| Status | IFR, IFD, IFC, As-Built, etc. | Yes |
| Issue Date | Date of current revision | Yes |
| Originator | Author/preparer | Yes |
| Reviewer | Checker/reviewer name | Yes |
| Approver | Approval authority | Yes |
| Transmittal Reference | Transmittal number for submissions | **ASSUMPTION** |
| TM Document Control Reference | TM EDMS reference | **TBD** |

---

## 3. Conditions

### 3.1 Prerequisites

- TM-provided MDR template or format requirements
- Document/tag numbering conventions from TM (ref: DEL-00.02)
- TM EDMS access and metadata requirements

### 3.2 Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Document Numbering Convention | TM / DEL-00.02 | **TBD** |
| TM EDMS Compatibility Requirements | TM | **TBD** |
| Discipline Deliverable Lists | PKG-01 through PKG-09 | Pending |

### 3.3 Constraints

- MDR must be compatible with TM EDMS
- All documents listed must follow TM naming conventions
- Register must be updated within **TBD** days of any document revision

---

## 4. Construction / Compilation

### 4.1 Development Approach

| Phase | Activity |
|-------|----------|
| Initialization | Obtain TM template; establish baseline structure |
| FEED | Populate with all FEED deliverables; maintain through IFD |
| Detailed Design | Continue updates through IFC |
| Closeout | Final update for FD package assembly |

### 4.2 Update Frequency

- **ASSUMPTION:** Weekly updates during active engineering phases
- Submission frequency per TM requirements (**TBD**)

### 4.3 Quality Control

- Internal review prior to each external submission
- Cross-check against transmittal records
- Verification against TM EDMS holdings

---

## 5. References

### 5.1 Source Documents

| Reference | Document | Section |
|-----------|----------|---------|
| SOW-0104 | Exhibit A - Scope of Work PS.pdf | Section 1.4 |
| SOW-0208 | Exhibit A - Scope of Work PS.pdf | Section 3.2.2.7 |
| SOW-0209 | Exhibit A - Scope of Work PS.pdf | Section 3.2.2.8-3.2.2.9 |
| SOW-0420 | Exhibit A - Scope of Work PS.pdf | Section 4.1.5 |
| SOW-0430 | Exhibit A - Scope of Work PS.pdf | Section 4.2.5 |
| SOW-0441 | Exhibit A - Scope of Work PS.pdf | Section 4.3.3.1-4.3.4.3 |
| SOW-0442 | Exhibit A - Scope of Work PS.pdf | Section 4.3.5.1-4.3.9.7 |

### 5.2 Related Deliverables

| Deliverable ID | Name | Relationship |
|----------------|------|--------------|
| DEL-00.02 | Document & Tag Numbering Instruction Plan | Provides numbering conventions |
| DEL-00.16 | Final Documentation (FD) Package | MDR serves as index |
| DEL-00.17 | Final Report | MDR referenced in report |

### 5.3 Applicable Standards

- TMP Standards and Specifications (**TBD** - Attachment A08 not available)
- TM EDMS requirements (**TBD**)

---

## 6. Notes and Assumptions

1. **ASSUMPTION:** MDR format will be provided by TM as a template.
2. **ASSUMPTION:** Weekly update frequency is standard practice; actual frequency TBD per TM requirements.
3. **TBD:** TM EDMS metadata requirements not yet available.
4. **TBD:** Specific document numbering conventions pending from TM.

---

*Generated: Pass 1 - Initial Draft, Pass 2 - Consistency Check*
*Source: PSO Decomposition REVISED v2, DEL-00.01 Context*
