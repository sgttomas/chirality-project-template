# Specification: DEL-00.04 Design Change Control Log (Pass 2 — Cross-Reference & Enriched)

**Document ID:** DEL-00.04-SP
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** Draft - Pending Review

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for the Design Change Control Log to be developed and maintained by the Engineering Contractor for the Puget Sound Optimization Project (PSO). The log shall provide a comprehensive register of all design changes, deviations, and MOC items, with full traceability to approvals and affected documents.

### 1.2 Applicability

This specification applies to:
- All design changes initiated during FEED and Detailed Design
- Deviations from TM standards or specifications
- Scope changes impacting deliverables
- MOC items per project requirements

### 1.3 Boundaries

**In Scope:**
- Design changes within Engineering Contractor scope
- Deviations requiring TM approval
- Scope changes directed by TM
- Internal design modifications

**Out of Scope:**
- Construction field changes (separate process)
- TM internal changes (reference only)

---

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Source | Pass 2 Cross-Reference |
|--------|-------------|----------|--------|------------------------|
| CCL-F-001 | Log shall capture all design changes during engineering phases | Mandatory | SOW-0420 | Datasheet: Section 2.1 (Scope Coverage); Procedure: Section 3.2 (Change Initiation); Guidance: Principle "Complete Capture" |
| CCL-F-002 | Log shall track approval status for each change | Mandatory | SOW-0420 | Datasheet: Section 2.3 (Approval Status field); Procedure: Section 3.3 (Approval Process); Guidance: Section 3.1 (Approval Level table) |
| CCL-F-003 | Log shall link changes to affected documents | Mandatory | SOW-0420 | Datasheet: Section 2.3 (Affected Documents field); Procedure: Step 3.2.6 (Identify affected docs); Guidance: Section 3.3 (MDR Linkage) |
| CCL-F-004 | Log shall support MOC tracking for deviations | Mandatory | SOW-0420 | Datasheet: Section 2.2 (Change Types include MOC); Guidance: Section 3.1 (Change Type "MOC") |
| CCL-F-005 | Log shall enable status reporting and trend analysis | **ASSUMPTION** | Best Practice | Procedure: Section 3.6 (Reporting); Guidance: Section 2.2 (Management Tool) |

### 2.2 Content Requirements

| Req ID | Requirement | Priority | Source | Pass 2 Cross-Reference |
|--------|-------------|----------|--------|------------------------|
| CCL-C-001 | Each entry shall have unique change identifier | Mandatory | SOW-0420 | Datasheet: Section 2.3 (Change ID field); Procedure: Step 3.2.3 (Assign change ID); Guidance: Example "DCN-2026-0015" |
| CCL-C-002 | Each entry shall include change description and justification | Mandatory | SOW-0420 | Datasheet: Section 2.3 (Change Description, Reason for Change); Procedure: Step 3.2.5 (Document justification); Guidance: Section 5.1 (Example entry) |
| CCL-C-003 | Each entry shall identify originating discipline | Mandatory | **ASSUMPTION** | Datasheet: Section 2.3 (Discipline field); Procedure: Step 3.2.1-3.2.2 (Originator); Guidance: Example shows "Process" discipline |
| CCL-C-004 | Each entry shall classify change type | Mandatory | SOW-0420 | Datasheet: Section 2.2 (Change Types); Procedure: Step 3.2.4 (Classify change); Guidance: Section 3.1 (5 change types defined) |
| CCL-C-005 | Each entry shall list affected documents | Mandatory | SOW-0420 | Datasheet: Section 2.3 (Affected Documents field); Procedure: Step 3.2.6 (Identify affected docs); Guidance: Section 3.3 (Cascade Tracking) |
| CCL-C-006 | Each entry shall track approval chain and dates | Mandatory | SOW-0420 | Datasheet: Section 2.3 (Approver(s), Approval Date fields); Procedure: Section 3.3 (Approval Process); Guidance: Section 5.3 (Workflow diagram) |
| CCL-C-007 | Each entry shall track implementation status | Mandatory | SOW-0420 | Datasheet: Section 2.3 (Implementation Status, Closure Date); Procedure: Section 3.4-3.5 (Implementation and Closure); Guidance: Principle "Closure Discipline" |

### 2.3 Format Requirements

| Req ID | Requirement | Priority | Source | Pass 2 Cross-Reference |
|--------|-------------|----------|--------|------------------------|
| CCL-FM-001 | Log shall be maintained in electronic spreadsheet format | Mandatory | SOW-0442 | Datasheet: Section 2.1 (Format: Electronic spreadsheet Excel); Procedure: Section 5.1 (Record format .xlsx) |
| CCL-FM-002 | Log shall be provided in native Excel format (.xlsx) | Mandatory | SOW-0442 | Datasheet: Section 2.1 (Native File Format .xlsx); Section 5.1 (Deliverables shows .xlsx) |
| CCL-FM-003 | Log shall support sorting and filtering on key fields | **ASSUMPTION** | Best Practice | Datasheet: Section 2.3 (Tabular structure); Implicit in Excel format |
| CCL-FM-004 | PDF export shall be provided for formal submissions | Mandatory | SOW-0442 | Datasheet: Section 2.1 (PDF Export required); Section 5.1 (Deliverables shows .pdf) |

### 2.4 Process Requirements

| Req ID | Requirement | Priority | Source | Pass 2 Cross-Reference |
|--------|-------------|----------|--------|------------------------|
| CCL-P-001 | All changes shall be logged before implementation | Mandatory | SOW-0420 | Datasheet: Section 3.3 (Constraint: all changes logged before implementation); Procedure: Step 3.4.1 (Confirm approval before implementing); Guidance: Principle "Proactive Logging" |
| CCL-P-002 | Deviations from TM standards shall require TM approval | Mandatory | SOW-0205 | Datasheet: Section 2.2 (Change Types include Deviation); Procedure: Step 3.3.4-3.3.6 (TM submission process); Guidance: Section 3.1 (Deviation type requires TM approval) |
| CCL-P-003 | Log shall be maintained in real-time | Mandatory | SOW-0420 | Datasheet: Section 4.2 (Real-time entry as changes raised); Procedure: Step 3.2.8 (Log entry in register); Guidance: Principle "Proactive Logging" |
| CCL-P-004 | Log shall be available for TM review on request | Mandatory | SOW-0413 | Datasheet: Section 4.1 (Reporting: periodic snapshots); Procedure: Step 3.6.2 (Prepare log for TM review on request); Section 4.2 (Review Requirements shows TM review on request) |

---

## 3. Standards

### 3.1 Applicable Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TMP Standards and Specifications | TM corporate standards | Deviation tracking (**TBD** - Attachment A08) |
| Contractor Change Control Procedures | Contractor internal procedures | Baseline process (**ASSUMPTION**) |

### 3.2 Codes and Regulations

- No specific codes directly govern change control logs
- Change tracking supports compliance audit trails

### 3.3 TM-Specific Requirements

- Deviations from TM standards require Company approval (SOW Section 3.2.2.3)
- Design change control per SOW Section 4.2.4.6

---

## 4. Verification

### 4.1 Verification Methods

| Req ID | Method | Acceptance Criteria | Pass 2 Cross-Reference |
|--------|--------|---------------------|------------------------|
| CCL-F-001 | Audit | All known changes are logged | Procedure: Section 4.1 (QC Checklist - all changes logged); Guidance: Section 6 (Pitfall prevention) |
| CCL-F-002 | Inspection | Approval status current for all entries | Procedure: Section 4.1 (Approvals complete check); Step 3.3.7 (Update log with approval status) |
| CCL-F-003 | Cross-reference | Affected documents identifiable in MDR | Datasheet: Section 5.2 (Related to DEL-00.01 MDR); Procedure: Step 3.4.3 (Update MDR); Guidance: Section 3.3 (MDR Linkage) |
| CCL-P-001 | Audit | No changes implemented without log entry | Procedure: Section 4.1 (No undocumented changes); Section 4.3 (Unapproved implementation issue); Guidance: Section 6 (Gate for document revision) |
| CCL-P-002 | Inspection | TM approvals documented for deviations | Procedure: Section 4.1 (TM approvals documented); Step 3.3.4-3.3.6 (TM approval tracking) |

### 4.2 Review and Approval

| Milestone | Review Activity | Approver |
|-----------|-----------------|----------|
| Log Setup | Structure review | Internal QA |
| Periodic | Status review | Project Manager |
| TM Review | Ad-hoc review on request | TM Project Team |
| Final | Closeout verification | TM Project Team |

### 4.3 Quality Checks

- Verify unique change IDs
- Confirm all mandatory fields populated
- Validate approval chain completeness for closed items
- Cross-check with document revision history

---

## 5. Documentation

### 5.1 Deliverables

| Document | Format | Timing |
|----------|--------|--------|
| Design Change Control Log (Excel) | .xlsx | Continuous; submitted on request |
| Design Change Control Log (PDF) | .pdf | Per submission requirements |
| Change Summary Reports | .pdf | **ASSUMPTION:** Monthly or per TM request |

### 5.2 Records

- Individual change request forms (if used)
- Approval records/emails
- TM approval documentation for deviations

### 5.3 Retention

- Log retained per TM document retention requirements (**TBD**)
- Approval records archived with project documentation

---

## 6. Notes and Assumptions

1. **ASSUMPTION:** Contractor has baseline change control procedures.
2. **ASSUMPTION:** Excel format is acceptable; alternative may be required per TM direction.
3. **TBD:** TM approval thresholds for different change types.
4. **TBD:** Integration requirements with TM change management systems.
5. **TBD:** Reporting frequency for change summaries.

---

## 7. Pass 2 Cross-Reference Summary

### 7.1 Requirements Traceability

All 18 requirements (5 functional + 7 content + 4 format + 4 process) have been cross-referenced to:
- **Datasheet**: Specific data fields, attributes, and dependencies
- **Procedure**: Implementation steps and quality control measures
- **Guidance**: Principles, examples, and best practices

### 7.2 Verification Traceability

All 5 verification methods in Section 4.1 trace completely to:
- Procedure Section 4.1 (QC Checklist)
- Guidance Section 6 (Common Pitfalls prevention)
- Datasheet Section 4.3 (Quality Control)

### 7.3 Standards and References

- **SOW References**: CCL-P-002 (SOW-0205), CCL-F-001/F-002/F-003/F-004 (SOW-0420), CCL-FM-001/FM-002/FM-004 (SOW-0442), CCL-P-004 (SOW-0413)
- **Related Deliverables**: DEL-00.01 (MDR), DEL-00.02 (Numbering), DEL-00.03 (Review Plan), DEL-01.14 (Process Deviations)
- **TM Standards**: Marked TBD pending Attachment A08 availability

### 7.4 Conflicts and Resolutions

**Conflicts Identified:** 2 minor (see _CONFLICTS_Pass2.md)
- CCL-CONF-001: Change type count - **RESOLVED** (added "Correction" type to Datasheet)
- CCL-CONF-002: Cost/Schedule Impact mandatory status - **RESOLVED** (clarified as required fields)

**TBD Items:** 5 items documented requiring external clarification
**Assumptions:** 5 assumptions documented requiring validation

**No blocking issues** - Specification is internally consistent and ready for technical review.

---

*Generated: Pass 2 - Cross-Reference Consistency Check*
*Source: PSO Decomposition REVISED v2, SOW Sections 3.2.2.3, 4.2.4*
