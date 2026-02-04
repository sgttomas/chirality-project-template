# Procedure: Line List

## 1. Purpose

### 1.1 Objective
This procedure defines the steps for creating, maintaining, and issuing the Line List for the Puget Sound Optimization Project.

### 1.2 Scope
Applicable to all piping within the PSO project scope at Sumas Tank Farm.

## 2. Prerequisites

### 2.1 Input Documents
| Document | Source | Status Required |
|----------|--------|-----------------|
| P&IDs | DEL-01.03 | IFD minimum |
| Process Data | DEL-01.08 | Approved |
| PMC Index | DEL-02.25 | Issued |
| Line Numbering Standard | TM Standard | Confirmed (**TBD**) |
| Equipment List | DEL-03.01 | Draft minimum |

### 2.2 Resources Required
- Piping Engineer (Lead)
- Piping Designer
- Access to 3D model (if available)
- Excel template per project standard

### 2.3 Training Requirements
- Familiarity with TM line numbering convention
- Knowledge of piping material classes
- Document control procedures

## 3. Steps

### 3.1 Preparation

| Step | Action | Responsible |
|------|--------|-------------|
| 3.1.1 | Obtain latest revision of all P&IDs | Piping Engineer |
| 3.1.2 | Obtain approved Line List template | Document Control |
| 3.1.3 | Confirm line numbering convention with TM | Piping Lead |
| 3.1.4 | Gather process data for design conditions | Piping Engineer |

### 3.2 Initial Population

| Step | Action | Responsible |
|------|--------|-------------|
| 3.2.1 | Extract all line numbers from P&IDs | Piping Designer |
| 3.2.2 | Enter line numbers into template | Piping Designer |
| 3.2.3 | Populate size and piping class | Piping Designer |
| 3.2.4 | Add from/to equipment references | Piping Designer |
| 3.2.5 | Enter service descriptions | Piping Engineer |

### 3.3 Design Data Population

| Step | Action | Responsible |
|------|--------|-------------|
| 3.3.1 | Enter design pressure and temperature | Piping Engineer |
| 3.3.2 | Enter operating pressure and temperature | Piping Engineer |
| 3.3.3 | Assign insulation requirements | Piping Engineer |
| 3.3.4 | Assign heat tracing requirements | Piping Engineer |
| 3.3.5 | Enter test requirements | Piping Engineer |
| 3.3.6 | Flag stress-critical lines | Stress Engineer |

### 3.4 Verification

| Step | Action | Responsible |
|------|--------|-------------|
| 3.4.1 | Cross-check against P&IDs for completeness | Piping Engineer |
| 3.4.2 | Verify design conditions against process data | Process Engineer |
| 3.4.3 | Validate piping classes against PMC Index | Piping Engineer |
| 3.4.4 | Check for duplicate line numbers | Piping Designer |
| 3.4.5 | Review by Lead Piping Engineer | Piping Lead |

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
| Completeness | All P&ID lines captured | Count verification |
| Uniqueness | No duplicate line numbers | Excel duplicate check |
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
| Line List | Excel + PDF | Project life + 10 years |
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
- Affected line numbers (for targeted updates)

### 5.4 SOW Traceability
| SOW Item | Description | Reference |
|----------|-------------|-----------|
| SOW-0117 | Produce FEED line list (LST) | SOW Section 3.1.3.1 (p7) |
| SOW-0250 | Develop Process Piping Line Designation Table (LDT) with required attributes | SOW Section 3.2.4.11 (p19) |

---
*Generated 2026-02-01 | SOW Refs: SOW-0117, SOW-0250*
