# Procedure: DEL-00.04 Design Change Control Log (Pass 2 — Cross-Reference & Enriched)

**Document ID:** DEL-00.04-PR
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** Draft - Pending Review

---

## 1. Purpose

### 1.1 Objective

This procedure defines the step-by-step process for establishing, maintaining, and reporting on the Design Change Control Log for the Puget Sound Optimization Project (PSO).

### 1.2 Scope

This procedure covers:
- Initial setup of the change control log
- Initiation and logging of design changes
- Approval workflow management
- Implementation tracking
- Closure and verification
- Reporting

---

## 2. Prerequisites

### 2.1 Required Inputs

| Input | Source | Status | Pass 2 Cross-Reference |
|-------|--------|--------|------------------------|
| Change Control Procedure | Contractor QA | Available (**ASSUMPTION**) | Specification: Section 3.1 (Contractor procedures); Datasheet: Section 3.2 (Dependency marked TBD) |
| Document Numbering Convention | DEL-00.02 | Pending | Datasheet: Section 3.2 (Dependency on DEL-00.02); Guidance: Section 3.3 (MDR Linkage) |
| MDR for Affected Document Links | DEL-00.01 | Pending | Specification: CCL-F-003 (Cross-reference to MDR); Datasheet: Section 5.2 (Related deliverable); Step 3.4.3 (Update MDR) |
| TM Approval Requirements | SOW | Available | Specification: CCL-P-002 (SOW-0205); Datasheet: Section 3.2 (Dependency on SOW); Section 2.3 (Approval authorizations) |
| Change ID Numbering Scheme | Contractor | To be established | Step 3.1.2 (Define numbering scheme); Section 5.3 (Example: DCN-[Year]-[Sequence]); Guidance: Example "DCN-2026-0015" |

### 2.2 Required Resources

| Resource | Description |
|----------|-------------|
| Change Control Coordinator | Manages log and tracks changes |
| Discipline Leads | Initiate and approve discipline changes |
| Project Manager | Approves significant changes |
| TM Contact | For scope changes and deviation approvals |

### 2.3 Required Authorizations

| Authorization | Holder |
|---------------|--------|
| Scope Changes | TM Project Team |
| Deviations from TM Standards | TM (per SOW) |
| Internal Design Modifications | Discipline Lead + Project Manager |

---

## 3. Steps

### 3.1 Log Setup

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1.1 | Create log spreadsheet with required fields | Change Control Coordinator | Blank log template |
| 3.1.2 | Define change ID numbering scheme | Change Control Coordinator | Numbering convention |
| 3.1.3 | Define change type classifications | Change Control Coordinator | Classification list |
| 3.1.4 | Define approval authorities per change type | Change Control Coordinator | Approval matrix |
| 3.1.5 | Distribute log location and access to team | Change Control Coordinator | Team notification |

### 3.2 Change Initiation

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.2.1 | Identify need for design change | Originator | Change concept |
| 3.2.2 | Complete change request form or log entry | Originator | Draft log entry |
| 3.2.3 | Assign unique change ID | Change Control Coordinator | Change ID assigned |
| 3.2.4 | Classify change type | Originator + Coordinator | Classification assigned |
| 3.2.5 | Document change description and justification | Originator | Description complete |
| 3.2.6 | Identify affected documents | Originator | Affected document list |
| 3.2.7 | Assess cost and schedule impact (if applicable) | Originator + Project Controls | Impact assessment |
| 3.2.8 | Log entry in register | Change Control Coordinator | Entry logged |

### 3.3 Approval Process

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.3.1 | Route change for internal technical review | Change Control Coordinator | Technical review request |
| 3.3.2 | Discipline lead reviews and approves/comments | Discipline Lead | Technical approval/comments |
| 3.3.3 | Originator addresses comments if needed | Originator | Revised change |
| 3.3.4 | For scope changes/deviations: prepare TM submission | Change Control Coordinator | TM submission package |
| 3.3.5 | Submit to TM and track response | Change Control Coordinator | TM tracking |
| 3.3.6 | Receive TM approval/rejection | Change Control Coordinator | TM decision |
| 3.3.7 | Update log with approval status and dates | Change Control Coordinator | Log updated |
| 3.3.8 | Communicate approval to originator | Change Control Coordinator | Approval notification |

### 3.4 Implementation

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.4.1 | Confirm approval before implementing | Originator | Approval verified |
| 3.4.2 | Revise affected documents | Originator/Discipline | Revised documents |
| 3.4.3 | Update MDR with revised document information | Document Controller | MDR updated |
| 3.4.4 | Update log with implementation status | Change Control Coordinator | Log updated |

### 3.5 Closure

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.5.1 | Verify all affected documents have been revised | Change Control Coordinator | Verification complete |
| 3.5.2 | Confirm revisions issued at appropriate status | Document Controller | Issue confirmation |
| 3.5.3 | Obtain closure sign-off | Discipline Lead | Closure approval |
| 3.5.4 | Update log with closure date and status | Change Control Coordinator | Log closed |

### 3.6 Reporting

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.6.1 | Generate weekly change summary (internal) | Change Control Coordinator | Weekly summary |
| 3.6.2 | Prepare change log for TM review (on request) | Change Control Coordinator | Log export |
| 3.6.3 | Report change metrics at progress meetings | Project Manager | Progress report input |

---

## 4. Verification

### 4.1 Quality Control Checklist

| Check Item | Verification Method | Pass Criteria | Pass 2 Cross-Reference |
|------------|---------------------|---------------|------------------------|
| All changes logged | Audit against document revisions | No undocumented changes | Specification: CCL-F-001 (Verification method); Guidance: Section 6 (Pitfall: changes not logged); Datasheet: Section 4.3 (QC: verify all changes logged) |
| Unique IDs assigned | Log inspection | No duplicates | Specification: CCL-C-001; Datasheet: Section 2.3 (Change ID field); Step 3.2.3 (Assign unique ID) |
| Approvals complete | Log inspection | All closed items have approvals | Specification: CCL-F-002 (Verification); Datasheet: Section 2.3 (Approval Status field); Step 3.3.7 (Update approval status) |
| Affected docs identified | Cross-reference MDR | Documents traceable | Specification: CCL-F-003 (Verification); Step 3.2.6 (Identify affected docs); Step 3.4.3 (Update MDR); Guidance: Section 3.3 |
| TM approvals documented | Record inspection | Evidence for all TM-required items | Specification: CCL-P-002 (Verification); Steps 3.3.4-3.3.6 (TM approval process); Guidance: Section 3.1 (TM approval required for Scope/Deviation) |

### 4.2 Review Requirements

| Milestone | Reviewer | Approval |
|-----------|----------|----------|
| Log Setup | QA Lead | Internal |
| Weekly | Project Manager | Internal |
| TM Review | TM Project Team | On request |
| Closeout | TM Project Team | Final |

### 4.3 Issue Resolution

| Issue Type | Resolution Process |
|------------|---------------------|
| Unapproved implementation | Stop work; complete approval; log NCR if needed |
| Missing log entry | Add retroactively; document reason |
| TM rejection | Document rejection; revise or revert design |

---

## 5. Records

### 5.1 Generated Records

| Record | Format | Retention |
|--------|--------|-----------|
| Design Change Control Log | .xlsx | Project duration + **TBD** years |
| Change Request Forms (if used) | .pdf | Project duration + **TBD** years |
| TM Approval Records | .pdf / email | Project duration + **TBD** years |
| Weekly Change Summaries | .pdf | Project duration + **TBD** years |
| Closure Sign-offs | Electronic | Project duration + **TBD** years |

### 5.2 Storage Location

- Log: Contractor document management system
- Approval records: With log or in transmittal files
- TM submissions: TM EDMS (**TBD**)

### 5.3 Naming Convention

- **ASSUMPTION:** `[Project Number]-CCL-[Date].xlsx`
- Example: `2500-CCL-20260301.xlsx`
- Change IDs: `DCN-[Year]-[Sequence]` (e.g., DCN-2026-0001)

---

## 6. Notes and Assumptions

1. **ASSUMPTION:** Contractor has baseline change control procedures to adapt.
2. **ASSUMPTION:** Weekly internal reporting frequency.
3. **TBD:** TM approval thresholds for different change types.
4. **TBD:** TM change management system integration requirements.
5. **TBD:** Document retention period not specified.

---

## 7. Revision History

| Revision | Date | Description | Author |
|----------|------|-------------|--------|
| Pass 1 | 2026-02-01 | Initial draft - Pass 1 generation | PSO Team |

---

## 8. Pass 2 Cross-Reference Summary

### 8.1 Process Flow Consistency

The 6-phase procedure (Sections 3.1-3.6) aligns completely with:
- **Specification Requirements**: All functional (CCL-F-xxx), content (CCL-C-xxx), format (CCL-FM-xxx), and process (CCL-P-xxx) requirements are addressed in procedure steps
- **Datasheet Structure**: Steps reference data fields in Datasheet Section 2.3
- **Guidance Principles**: Steps implement the 5 core principles from Guidance Section 2.1

### 8.2 Key Step Cross-References

| Procedure Section | Cross-References |
|-------------------|------------------|
| 3.1 Log Setup | Datasheet Section 4.1 (Development Approach); Specification CCL-C-001 (unique IDs) |
| 3.2 Change Initiation | Specification CCL-C-001 through CCL-C-005; Datasheet Section 2.3 (all data fields); Guidance Section 5.1 (example) |
| 3.3 Approval Process | Specification CCL-P-002 (TM approval); Guidance Section 3.1 (approval levels); Section 5.3 (workflow diagram) |
| 3.4 Implementation | Specification CCL-P-001 (log before implementation); Guidance Principle "Proactive Logging" |
| 3.5 Closure | Specification CCL-C-007 (implementation status); Guidance Principle "Closure Discipline" |
| 3.6 Reporting | Specification CCL-P-004 (TM review on request); Datasheet Section 4.2 (weekly assumption) |

### 8.3 Verification Traceability

All QC checklist items (Section 4.1) trace to:
- Specification verification methods (Section 4.1)
- Guidance pitfall prevention strategies (Section 6)
- Datasheet quality control section (Section 4.3)

### 8.4 TBD Items Identified

1. **Document Retention Period**: Marked TBD in Section 5.1 records retention
2. **TM Approval Thresholds**: Noted in Section 6 (assumptions)
3. **TM EDMS Location**: Marked TBD in Section 5.2 (storage location)
4. **Change Control Procedure**: Assumption in Section 2.1 (required input)

---

*Generated: Pass 2 - Cross-Reference Consistency Check*
*Source: PSO Decomposition REVISED v2, SOW Sections 3.2.2.3, 4.2.4*
