# Procedure: Valve List (Piping)

## 1. Purpose

### 1.1 Objective
This procedure defines the steps for creating, maintaining, and issuing the Valve List for the Puget Sound Optimization Project.

### 1.2 Scope
Applicable to all piping valves within the PSO project scope at Sumas Tank Farm.

## 2. Prerequisites

### 2.1 Input Documents
| Document | Source | Status Required |
|----------|--------|-----------------|
| P&IDs | DEL-01.03 | IFD minimum |
| Line List | DEL-02.01 | Draft minimum |
| PMC Index | DEL-02.25 | Issued |
| Valve Tagging Standard | TM Standard | Confirmed (**TBD**) |
| I&C Requirements | DEL-07.xx | Draft (for actuated valves) |

### 2.2 Resources Required
- Piping Engineer (Lead)
- Piping Designer
- Access to P&IDs and line list
- Excel template per project standard

### 2.3 Training Requirements
- Familiarity with TM valve tagging convention
- Knowledge of valve types and applications
- Document control procedures

## 3. Steps

### 3.1 Preparation

| Step | Action | Responsible |
|------|--------|-------------|
| 3.1.1 | Obtain latest revision of all P&IDs | Piping Engineer |
| 3.1.2 | Obtain approved Valve List template | Document Control |
| 3.1.3 | Confirm valve tagging convention with TM | Piping Lead |
| 3.1.4 | Obtain Line List for line number references | Piping Engineer |

### 3.2 Initial Population

| Step | Action | Responsible |
|------|--------|-------------|
| 3.2.1 | Extract all valves from P&IDs | Piping Designer |
| 3.2.2 | Enter valve tags into template | Piping Designer |
| 3.2.3 | Enter associated line numbers | Piping Designer |
| 3.2.4 | Populate valve type and size | Piping Designer |
| 3.2.5 | Enter service descriptions | Piping Engineer |

### 3.3 Technical Data Population

| Step | Action | Responsible |
|------|--------|-------------|
| 3.3.1 | Enter pressure rating/class | Piping Engineer |
| 3.3.2 | Enter material class designation | Piping Engineer |
| 3.3.3 | Enter end connection type | Piping Engineer |
| 3.3.4 | Enter operator type | Piping Engineer |
| 3.3.5 | Enter fail position (actuated valves) | Piping Engineer |
| 3.3.6 | Add P&ID and specification references | Piping Designer |

### 3.4 Verification

| Step | Action | Responsible |
|------|--------|-------------|
| 3.4.1 | Cross-check against P&IDs for completeness | Piping Engineer |
| 3.4.2 | Verify line number references against Line List | Piping Designer |
| 3.4.3 | Validate piping classes against PMC Index | Piping Engineer |
| 3.4.4 | Verify actuator requirements with I&C | Piping Engineer |
| 3.4.5 | Check for duplicate valve tags | Piping Designer |
| 3.4.6 | Review by Lead Piping Engineer | Piping Lead |

### 3.5 Issue and Maintenance

| Step | Action | Responsible |
|------|--------|-------------|
| 3.5.1 | Submit for internal review | Piping Engineer |
| 3.5.2 | Incorporate review comments | Piping Designer |
| 3.5.3 | Submit for Owner review | Document Control |
| 3.5.4 | Issue approved revision | Document Control |
| 3.5.5 | Update for subsequent P&ID revisions | Piping Engineer |

## 4. Verification

### 4.1 Quality Checks

| Check | Criteria | Method |
|-------|----------|--------|
| Completeness | All P&ID valves captured | Count verification |
| Uniqueness | No duplicate valve tags | Excel duplicate check |
| Accuracy | Data matches source documents | Sample audit (10%) |
| Format | Template compliance | Visual review |

### 4.2 Review and Approval

| Role | Responsibility |
|------|----------------|
| Piping Designer | Prepare and self-check |
| Piping Engineer | Technical review |
| Piping Lead | Approve for issue |
| TM Representative | Owner review and approval |

## 5. Records

### 5.1 Records Generated

| Record | Format | Retention |
|--------|--------|-----------|
| Valve List | Excel + PDF | Project life + 10 years |
| Review comments | PDF/Email | Project life |
| Approval records | PDF | Project life + 10 years |

### 5.2 Document Control

| Aspect | Requirement |
|--------|-------------|
| **Numbering** | Per TM document numbering (**TBD**) |
| **Revision Control** | Track all revisions with revision history |
| **Distribution** | Per project distribution matrix |
| **Storage** | Project document management system |

### 5.3 Revision History Tracking
Each revision shall document:
- Revision number and date
- Description of changes
- Prepared by / Checked by / Approved by
- Affected valve tags (for targeted updates)

### 5.4 SOW Traceability
| SOW Item | Description | Reference |
|----------|-------------|-----------|
| SOW-0120 | Produce FEED valve list (VLL) | SOW Section 3.1.3.1 (p7-8) |
| SOW-0119 | Produce FEED mechanical/electrical datasheets for valves (incl check valves/actuators) | SOW Section 3.1.3.1 (p7) |

---
*Generated 2026-02-01 | SOW Refs: SOW-0119, SOW-0120*
