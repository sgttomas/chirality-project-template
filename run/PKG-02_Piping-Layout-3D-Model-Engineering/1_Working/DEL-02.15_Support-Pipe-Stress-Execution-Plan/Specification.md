# Specification: DEL-02.15 Support & Pipe Stress Execution Plan

## 1. Scope

### 1.1 Purpose
This specification defines the requirements for developing the Support & Pipe Stress Execution Plan for the Puget Sound Optimization (PSO) Project at Sumas Tank Farm. This plan shall define the methodology, tools, and procedures for pipe support design and stress analysis, establishing the framework for all stress-related deliverables.

### 1.2 Applicability
- Defines scope of stress analysis across the PSO project
- Establishes critical line identification criteria
- Defines analysis methodology and software
- Establishes support design philosophy
- Governs production of DEL-02.14 (Stress Reports), DEL-02.16 (Support Standards), DEL-02.17 (Support Location Plans)

### 1.3 Scope Boundaries

| In Scope | Out of Scope |
|----------|--------------|
| Analysis methodology definition | Actual stress analysis (DEL-02.14) |
| Critical line screening criteria | Detailed support structural design (PKG-04) |
| Support design philosophy | Support fabrication procedures |
| Load case definitions | Equipment thermal growth calculations |
| Quality assurance approach | Welding procedures |
| Interface definitions | Pressure design calculations |

## 2. Requirements

### 2.1 Plan Content Requirements

| Req ID | Requirement | Priority | Verification Method |
|--------|-------------|----------|---------------------|
| EPR-001 | Define critical line screening criteria | Mandatory | Plan review |
| EPR-002 | List all applicable codes and standards | Mandatory | Plan review |
| EPR-003 | Specify stress analysis software to be used | Mandatory | Plan review |
| EPR-004 | Define all required load cases per applicable codes | Mandatory | Code check |
| EPR-005 | Define support design philosophy and standard types | Mandatory | Plan review |
| EPR-006 | List all stress-related deliverables | Mandatory | Plan review |
| EPR-007 | Define interface requirements with other disciplines | Mandatory | Plan review |
| EPR-008 | Define quality check and review requirements | Mandatory | Plan review |
| EPR-009 | Include schedule milestones aligned with project | Mandatory | Schedule check |
| EPR-010 | Address existing system verification approach per SOW-0240 | Mandatory | Plan review |

### 2.2 Critical Line Criteria Requirements

| Criterion | Typical Threshold (ASSUMPTION - confirm with TM) |
|-----------|--------------------------------------------------|
| Operating Temperature | > 65C (150F) or < -30C (-20F) |
| Pipe Size | NPS 12 and larger |
| Rotating Equipment | All pump suction and discharge lines |
| Sensitive Equipment | Lines connected to heat exchangers, vessels |
| High Pressure | Lines with design pressure > TBD |
| Special Piping | Jacketed piping, lines with expansion joints |
| Tie-Ins | All tie-ins to existing systems |
| Project-Designated | Lines designated as critical by project |

### 2.3 Load Case Requirements

| Load Case Category | Load Cases Required |
|--------------------|---------------------|
| Sustained | Weight + Pressure (W+P) |
| Thermal Expansion | Operating temperature ranges |
| Occasional | Wind, earthquake (if applicable) |
| Test | Hydrostatic test conditions |
| Transient | Startup/shutdown (if significant) |

### 2.4 Format Requirements

| Aspect | Requirement |
|--------|-------------|
| Document Format | PDF per TMP document standards |
| Structure | Per Section 4.1 of Datasheet |
| Appendices | Critical line list, support standards, templates |
| Revision Control | Per TMP document control procedures |

## 3. Standards

### 3.1 Governing Codes and Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TMP Standards & Specifications | Trans Mountain project standards | Primary (Attachment A08 - TBD) |
| CSA Z662 | Oil and gas pipeline systems | Pipeline stress requirements |
| ASME B31.3 | Process Piping | Station piping stress |
| ASME B31.4 | Pipeline Transportation | If applicable |
| API 610 | Centrifugal Pumps | Pump nozzle allowables |
| API 617 | Centrifugal Compressors | If applicable |

### 3.2 Project-Specific Standards

| Standard | Description |
|----------|-------------|
| TMP Stress Analysis Standards | Specific requirements (TBD) |
| TMP Support Design Standards | Support types, details (TBD) |
| Drawing Numbering | Per Document & Tag Numbering Plan (DEL-00.02) |

### 3.3 Software Standards
- Stress analysis software shall be industry-standard (e.g., CAESAR II, AutoPIPE)
- Software shall be licensed and validated for applicable codes
- Native files shall be deliverable per SOW-0259

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Application |
|--------|-------------|-------------|
| Plan Review | Technical review of plan content | All requirements |
| Code Check | Verify load cases per applicable codes | Code compliance |
| Interface Review | Verify interfaces with related disciplines | Coordination |
| TM Approval | Owner review and approval | Overall acceptance |

### 4.2 Acceptance Criteria

| Criterion | Acceptance Standard |
|-----------|---------------------|
| Completeness | All required sections addressed |
| Code Coverage | All applicable codes referenced |
| Methodology | Clear, practical analysis approach |
| Interfaces | All interfaces defined and agreed |
| Schedule | Milestones aligned with project schedule |
| TM Approval | Approved before stress analysis begins |

### 4.3 Review Stages

| Stage | Review Type | Participants | Output |
|-------|-------------|--------------|--------|
| Draft | Internal review | Piping, Stress, Structural | Comments |
| Issue for Review | TM review | TM Engineering | Comments |
| Approved | TM approval | TM | Approved plan |

## 5. Documentation

### 5.1 Deliverable Components

| Component | Format | Requirement |
|-----------|--------|-------------|
| Execution Plan Document | PDF | Required |
| Critical Line List (Appendix) | Excel | Required |
| Support Standard Summary (Appendix) | PDF | Required |
| MDR Entry | Per DEL-00.01 | Required |

### 5.2 Submission Requirements
- Submit plan per TM document control procedures (SOW-0430)
- Register in MDR (DEL-00.01) with appropriate metadata
- Obtain TM approval before stress analysis work begins

### 5.3 Revision Control
- Plan revision tracking per TMP procedures
- Document all revisions with description of changes
- Re-approval required for significant methodology changes

### 5.4 Cross-References

| Document | Purpose |
|----------|---------|
| DEL-02.01 | Line List - scope definition |
| DEL-02.14 | Stress Reports - analysis deliverables |
| DEL-02.16 | Support Standard Drawings - support details |
| DEL-02.17 | Support Location Plans - support locations |
| PKG-04 | Structural - support structural design interface |

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
