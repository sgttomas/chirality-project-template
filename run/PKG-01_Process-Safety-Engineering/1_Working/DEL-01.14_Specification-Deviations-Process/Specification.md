# Specification: DEL-01.14 Specification Deviations (Process)

**Document ID:** DEL-01.14-SP
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for the Process Specification Deviations Register, which documents and tracks all process-related deviations from Trans Mountain (TM) standards and specifications for the Puget Sound Optimization (PSO) project.

### 1.2 Boundaries

- **In Scope:** All process engineering deviations from TM standards, including:
  - Process design criteria deviations
  - Equipment specification deviations (process-related)
  - Material selection deviations (process systems)
  - Operating parameter deviations
  - Safety-related design deviations

- **Out of Scope:**
  - Electrical discipline deviations (tracked separately)
  - Instrumentation discipline deviations (tracked separately)
  - Civil/Structural discipline deviations (tracked separately)
  - Piping discipline deviations (unless process-driven)

### 1.3 Interfaces

| Interface | Description |
|-----------|-------------|
| TM Engineering Standards | Source documents for standard requirements |
| TM Approval Process | Governance for deviation approval |
| Other Discipline Registers | Coordination of multi-discipline deviations |
| Design Documents | P&IDs, datasheets, calculations affected by deviations |
| HAZOP | Safety review of deviation impacts |

---

## 2. Requirements

### 2.1 Functional Requirements

| ID | Requirement | Priority |
|----|-------------|----------|
| REQ-01 | Register shall capture all process deviations from TM standards | Mandatory |
| REQ-02 | Each deviation shall have unique identifier | Mandatory |
| REQ-03 | Each deviation shall include technical justification | Mandatory |
| REQ-04 | Each deviation shall include risk assessment | Mandatory |
| REQ-05 | TM approval status shall be tracked for each deviation | Mandatory |
| REQ-06 | Register shall be maintained current throughout project | Mandatory |
| REQ-07 | Affected documents shall be cross-referenced | Mandatory |
| REQ-08 | Register shall support filtering/sorting by status | Recommended |

### 2.2 Data Requirements

| Data Element | Requirement |
|--------------|-------------|
| Deviation ID | Unique alphanumeric identifier following project convention (e.g., SD-PR-###) |
| Standard Reference | Specific clause/section of TM standard |
| Description | Clear, complete description of deviation |
| Justification | Technical and/or commercial basis for deviation |
| Risk Assessment | Safety, reliability, cost, and schedule impact evaluation (Low/Medium/High scale) |
| Approval Status | Tracked through complete approval workflow |

### 2.3 Process Requirements

| Requirement | Description |
|-------------|-------------|
| Identification | Deviations identified as soon as recognized during design |
| Documentation | Complete documentation before submission for approval |
| Approval | TM approval obtained before implementing deviation |
| Approval Timing | Allow adequate time for TM review: Minor (2 weeks), Significant (4 weeks), Major (6+ weeks) |
| Implementation | Deviation reflected in design documents after approval |
| Closeout | Final verification that deviation properly implemented |

---

## 3. Standards

### 3.1 Applicable Standards

| Standard | Description |
|----------|-------------|
| TM Engineering Standards | Company standards from which deviations occur (**TBD** - specific list) |
| TM Management of Change | Process for approving changes/deviations |
| CSA Z662 | Oil and Gas Pipeline Systems (regulatory baseline) |
| API Standards | Industry standards for petroleum facilities |

### 3.2 Compliance Requirements

- All deviations from regulatory requirements (CSA Z662) require documented engineering assessment
- Safety-critical deviations require HAZOP review
- **ASSUMPTION:** TM has established deviation approval process and templates

### 3.3 Quality Requirements

| Requirement | Description |
|-------------|-------------|
| Completeness | All fields populated for each deviation entry |
| Accuracy | Information verified against source documents |
| Currency | Register updated within 5 business days of status change |
| Traceability | All approvals documented with reference numbers |

---

## 4. Verification

### 4.1 Verification Methods

| Requirement | Method | Acceptance Criteria |
|-------------|--------|---------------------|
| REQ-01 | Audit | No undocumented deviations found |
| REQ-02 | Review | All entries have unique IDs |
| REQ-03 | Review | All entries have justification text |
| REQ-04 | Review | All entries have risk assessment |
| REQ-05 | Review | TM approval reference documented |
| REQ-06 | Audit | No entries older than 5 days without update |
| REQ-07 | Cross-check | Referenced documents exist and are current |

### 4.2 Review Checklist

- [ ] All process deviations identified and documented
- [ ] Each deviation has complete justification
- [ ] Risk assessments consistent with deviation significance
- [ ] TM approvals obtained before implementation
- [ ] Design documents updated to reflect approved deviations
- [ ] Register format consistent with project requirements

### 4.3 Audit Requirements

| Audit Type | Frequency | Responsible |
|------------|-----------|-------------|
| Internal Review | Monthly | Lead Process Engineer |
| TM Review | Per TM project audit schedule | TM Engineering |
| Final Closeout | Project completion | Project Quality |

---

## 5. Documentation

### 5.1 Deliverable Documents

| Document | Format | Purpose |
|----------|--------|---------|
| Deviation Register | Excel/PDF | Primary tracking document |
| Deviation Request Forms | PDF | Individual deviation submissions (if required by TM) |
| Approval Records | PDF | TM approval documentation |

### 5.2 Supporting Documentation

- Deviation request packages (justification, drawings, calculations)
- TM approval correspondence
- HAZOP review records (where applicable)
- Design document revision records

### 5.3 Revision Control

- Register maintained as living document
- Revision history tracked for register updates
- Individual deviations tracked by status (not revision)
- **TBD** - Specific revision control per TM project procedures

---

*End of Specification*
