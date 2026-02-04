# Specification: DEL-00.06 Interface Register & Schedule

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-00.06 |
| Deliverable Name | Interface Register & Schedule |
| Revision | 0 (Initial Draft) |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## 1. Purpose and Scope
This specification defines the requirements for the Interface Register & Schedule to be maintained throughout the PSO project. The register shall capture all interfaces requiring coordination between parties, disciplines, and phases.

## 2. Applicable Standards and References
| Reference | Description |
|-----------|-------------|
| SOW Section 4.4.2.1-4.4.4.1 | Interface management requirements |
| TMP Standards and Specifications | As applicable (TBD - Attachment A08 not available) |
| DEL-00.05 | Interface Management Plan |

## 3. Requirements

### 3.1 Content Requirements
| Req ID | Requirement | Source | Verification |
|--------|-------------|--------|--------------|
| SPEC-06.01 | Register shall include all identified interfaces between TM and Engineering Contractor | SOW-0451 | Review |
| SPEC-06.02 | Register shall include all interfaces between Engineering Contractor and other contractors (e.g., MAC) | SOW-0451 | Review |
| SPEC-06.03 | Each interface entry shall identify the Interface Owner (person/role responsible for interface resolution) | SOW-0451 | Review |
| SPEC-06.04 | Each interface entry shall include a due date by which the interface must be resolved | SOW-0451 | Review |
| SPEC-06.05 | Register shall track interface status through to closure | SOW-0451 | Review |
| SPEC-06.06 | Register shall support access by authorized interface-related parties (including MAC and other contractors as applicable) | SOW-0451 | Review |

### 3.2 Format Requirements (ASSUMPTION)
| Req ID | Requirement | Source | Verification |
|--------|-------------|--------|--------------|
| SPEC-06.10 | Register shall be maintained in a controlled, revisable format (Excel or equivalent) | ASSUMPTION | Inspection |
| SPEC-06.11 | Register shall support export to PDF for distribution | ASSUMPTION | Demonstration |
| SPEC-06.12 | Register shall be compatible with TM EDMS requirements | SOW-0441 | Inspection |
| SPEC-06.13 | Register shall use naming convention INT-[Category]-[Sequential Number] for Interface IDs | ASSUMPTION | Inspection |

### 3.3 Schedule Integration Requirements (ASSUMPTION)
| Req ID | Requirement | Source | Verification |
|--------|-------------|--------|--------------|
| SPEC-06.20 | Interface due dates shall align with project schedule milestones | ASSUMPTION | Review |
| SPEC-06.21 | Register shall flag overdue or at-risk interfaces | ASSUMPTION | Review |
| SPEC-06.22 | Register shall support schedule impact assessment | ASSUMPTION | Review |

## 4. Quality Requirements
| Req ID | Requirement | Source |
|--------|-------------|--------|
| SPEC-06.30 | Register shall be subject to periodic review per Interface Management Plan | DEL-00.05 |
| SPEC-06.31 | Changes to interface entries shall be logged with date and modifier | SOW-0420 |

## 5. Deliverable Format
- Primary format: Microsoft Excel (.xlsx)
- Secondary format: PDF (for distribution/archival)
- Naming convention: Per TM document numbering requirements (TBD)

## 6. Acceptance Criteria
| Criterion | Description |
|-----------|-------------|
| AC-06.01 | All known interfaces are captured with required fields populated |
| AC-06.02 | Owner assignments are confirmed by responsible parties |
| AC-06.03 | Due dates are aligned with project schedule |
| AC-06.04 | Register is accessible to authorized parties per SOW requirements |

## 7. Open Items
| Item | Description | Resolution Target |
|------|-------------|-------------------|
| TBD-01 | Confirm TM template requirements | Prior to IFR submission |
| TBD-02 | Confirm EDMS metadata requirements | Prior to IFR submission |
| TBD-03 | Confirm interface categories per TM | Prior to IFR submission |
