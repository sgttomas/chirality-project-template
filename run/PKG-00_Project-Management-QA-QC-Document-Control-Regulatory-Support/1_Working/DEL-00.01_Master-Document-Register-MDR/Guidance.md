# Guidance: DEL-00.01 Master Document Register (MDR)

**Document ID:** DEL-00.01-GD
**Revision:** Pass 2 (Consistency Check)
**Date:** 2026-02-01
**Status:** Draft - Consistency Checked

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides practical direction for developing and maintaining the Master Document Register (MDR) for the Puget Sound Optimization Project (PSO). It supplements the formal Specification by offering context, best practices, and recommendations for effective implementation.

### 1.2 Audience

- Document Control personnel
- Engineering leads and discipline managers
- Project management team
- Quality assurance personnel

---

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Completeness** | Every document produced must be captured in the MDR without exception |
| **Accuracy** | Document information must match actual issued documents |
| **Currency** | MDR must reflect current status at all times |
| **Traceability** | Enable tracking of documents from creation through final issue |
| **Accessibility** | MDR must be easy to search, sort, and filter |

### 2.2 Guiding Philosophy

The MDR is the single source of truth for project document inventory. It serves multiple stakeholders:
- **TM Document Control:** Enables verification of deliverables received
- **Engineering Teams:** Provides visibility into document status across disciplines
- **Quality Assurance:** Supports audit and verification activities
- **Project Management:** Enables progress tracking and reporting

---

## 3. Considerations

### 3.1 Initial Setup Considerations

| Consideration | Guidance |
|---------------|----------|
| **Template Selection** | Confirm TM template availability before developing custom format. If no template provided, propose format to TM for approval before populating. |
| **Numbering Convention** | Coordinate with TM Document Control early to obtain numbering conventions. Reference DEL-00.02 for instruction plan. |
| **EDMS Compatibility** | Identify TM EDMS metadata fields early to ensure MDR structure supports required mappings. |

### 3.2 Ongoing Maintenance Considerations

| Consideration | Guidance |
|---------------|----------|
| **Update Frequency** | Establish a regular update cadence (recommend weekly minimum during active phases). |
| **Version Control** | Maintain clear revision history; do not overwrite previous versions without archiving. |
| **Multi-discipline Coordination** | Designate a single MDR owner; discipline leads provide inputs through structured process. |

### 3.3 Integration Considerations

| Consideration | Guidance |
|---------------|----------|
| **Transmittal Alignment** | Cross-reference MDR entries with transmittal logs to ensure consistency. |
| **Revision Status** | Clearly distinguish between draft revisions and formally issued revisions. |
| **Superseded Documents** | Retain entries for superseded documents with clear status indication. |

---

## 4. Trade-offs

### 4.1 Granularity vs. Manageability

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **High Granularity** (individual sheets/attachments listed) | Complete traceability; supports detailed audits | High maintenance burden; potential for errors |
| **Document-Level Only** | Manageable size; easier updates | May miss attachments or appended items |

**Recommendation:** Start with document-level tracking; add sub-document tracking only where explicitly required by TM or for regulatory traceability.

### 4.2 Update Frequency

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Real-time Updates** | Always current; no lag | High administrative burden |
| **Weekly Updates** | Balanced effort; reasonable currency | May miss short-term status questions |
| **Per-Transmittal Updates** | Aligned with formal submissions | May become outdated between submissions |

**Recommendation:** Weekly updates as baseline, with mandatory updates at each transmittal.

### 4.3 Format Choices

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Excel Spreadsheet** | Widely accessible; easy to filter/sort | Limited multi-user access |
| **Database System** | Multi-user; better integrity | Requires infrastructure; learning curve |
| **Document Management System** | Integrated with workflows | May not align with TM EDMS |

**Recommendation:** Use Excel format unless TM specifies otherwise; this aligns with typical industry practice and SOW native file requirements.

---

## 5. Examples

### 5.1 Sample MDR Structure

| Doc Number | Title | Type | Discipline | Rev | Status | Issue Date | Originator | Reviewer | Approver | Transmittal | TM EDMS Ref |
|------------|-------|------|------------|-----|--------|------------|------------|----------|----------|-------------|-------------|
| 2500-PKG01-PFD-001 | Process Flow Diagram - Booster Pump Station | Drawing | Process | A | IFR | 2026-03-15 | J. Smith | K. Brown | L. Davis | TR-001 | TBD |
| 2500-PKG01-DBM-001 | Design Basis Memorandum | Document | Process | 0 | IFD | 2026-04-01 | A. Johnson | M. Lee | P. White | TR-005 | TBD |
| 2500-PKG02-ISO-001 | Piping Isometric - Line 100-P-001 | Drawing | Piping | B | IFC | 2026-06-15 | M. Williams | R. Taylor | S. Green | TR-012 | TBD |

### 5.2 Status Code Definitions

| Status Code | Definition | Phase |
|-------------|------------|-------|
| DFT | Draft - Internal review | Any |
| IFR | Issued for Review | FEED |
| IFD | Issued for Design | End of FEED |
| IFC | Issued for Construction | Detailed Design |
| AB | As-Built | Post-Construction |

### 5.3 Revision Numbering Convention (**ASSUMPTION**)

- Numeric revisions (0, 1, 2...) for issued documents
- Alpha revisions (A, B, C...) for review drafts
- Confirm convention with TM Document Control

---

## 6. Common Pitfalls

| Pitfall | Prevention Strategy |
|---------|---------------------|
| **Missing Documents** | Implement check-in process where no document is transmitted without MDR entry |
| **Stale Information** | Establish mandatory update triggers tied to transmittals |
| **Inconsistent Numbering** | Use automated validation against numbering convention |
| **Duplicate Entries** | Implement unique constraint on document number field |
| **Lost Revisions** | Never delete or overwrite; mark superseded instead |

---

## 7. Conflict Table

The following items require clarification from TM or external sources:

| Item ID | Issue | Documents Affected | Priority | Resolution Needed From | Status |
|---------|-------|-------------------|----------|----------------------|--------|
| CT-01 | TM MDR template not yet provided | All | High | TM Document Control | Open |
| CT-02 | TM EDMS metadata requirements undefined | Datasheet, Specification, Procedure | High | TM Document Control | Open |
| CT-03 | Document numbering conventions pending | All | High | TM / DEL-00.02 | Open |
| CT-04 | Transmittal reference field priority unclear | Specification (MDR-C-008) | Medium | TM Document Control | Open |
| CT-05 | Document retention period not specified | Specification, Procedure | Medium | TM | Open |
| CT-06 | Update frequency to be confirmed | Datasheet, Specification | Medium | TM Project Team | Open |
| CT-07 | Attachment A08 (TM Standards) not available | Datasheet, Specification | Medium | TM | Open |

---

## 8. Notes and Assumptions

1. **ASSUMPTION:** Excel-based MDR is acceptable to TM; alternative may be required.
2. **ASSUMPTION:** Status codes shown are examples; actual codes to be confirmed with TM.
3. **ASSUMPTION:** Reviewer field is mandatory based on industry best practice.
4. **ASSUMPTION:** Revision convention (numeric for issued, alpha for draft) follows typical engineering practice.
5. **TBD:** TM EDMS integration requirements not yet available (see CT-02).
6. **TBD:** Specific TM template for MDR not yet provided (see CT-01).

---

*Generated: Pass 1 - Initial Draft, Pass 2 - Consistency Check*
*Source: PSO Decomposition REVISED v2, Industry Best Practices*
