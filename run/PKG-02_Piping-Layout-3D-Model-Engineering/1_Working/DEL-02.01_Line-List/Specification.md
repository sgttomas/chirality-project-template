# Specification: Line List

## 1. Scope

### 1.1 Purpose
This specification defines the requirements for developing and maintaining the Line List (LST) for the Puget Sound Optimization Project at Sumas Tank Farm.

### 1.2 Applicability
- All new piping associated with booster pump installation
- Modified existing piping
- Tie-in connections to existing systems
- Piping for 5x6 manifold system

### 1.3 Exclusions
- Instrument tubing (covered under Instrumentation package)
- Vendor package internal piping (unless specified)

## 2. Requirements

### 2.1 Content Requirements
The Line List shall include:

| Requirement | Description |
|-------------|-------------|
| REQ-01 | Unique line number for each pipe segment |
| REQ-02 | Nominal pipe size and schedule |
| REQ-03 | Piping material class designation |
| REQ-04 | Service description |
| REQ-05 | From/To equipment or line references |
| REQ-06 | Design pressure and temperature |
| REQ-07 | Operating pressure and temperature |
| REQ-08 | Insulation requirements |
| REQ-09 | Heat tracing requirements |
| REQ-10 | Test requirements (hydrotest pressure) |
| REQ-11 | P&ID reference |
| REQ-12 | Stress analysis criticality flag |

### 2.2 Format Requirements
- Excel spreadsheet format
- Sortable and filterable columns
- Version control and revision tracking
- Compatible with 3D model data extraction

### 2.3 Accuracy Requirements
- Line numbers shall match P&ID line designations exactly
- Design conditions shall be traceable to process data
- Material classes shall be validated against PMC Index

## 3. Standards

| Standard | Description |
|----------|-------------|
| ASME B31.3 | Process Piping (**ASSUMPTION**) |
| CSA Z662 | Oil and Gas Pipeline Systems (**ASSUMPTION**) |
| TM-SPEC-PIPE-001 | TM Piping Specification (**TBD**) |
| TM-STD-LINE-NUM | TM Line Numbering Standard (**TBD**) |

## 4. Verification

### 4.1 Verification Methods
| Method | Description |
|--------|-------------|
| Review | Technical review by Lead Piping Engineer |
| Cross-check | Verification against P&IDs |
| Validation | PMC class validation |
| Audit | Document control audit for completeness |

### 4.2 Acceptance Criteria
- 100% of lines on P&IDs are captured in Line List
- All mandatory fields populated
- No duplicate line numbers
- Design conditions verified against process data
- Owner review and approval

## 5. Documentation

### 5.1 Deliverable Format
- Native: Excel (.xlsx)
- PDF export for review/approval cycles

### 5.2 Submission Requirements
| Milestone | Status |
|-----------|--------|
| FEED IFR | Issue for Review |
| FEED IFD | Issue for Design |
| Detailed Design IFC | Issue for Construction |
| As-Built | Final as-built revision |

### 5.3 Related Documents
- DEL-01.03: P&IDs
- DEL-02.02: Valve List
- DEL-02.03: Tie-In List
- DEL-02.18: Line Designation Table
- DEL-02.25: PMC Index

### 5.4 SOW Traceability
| SOW Item | Description | Reference |
|----------|-------------|-----------|
| SOW-0117 | Produce FEED line list (LST) | SOW Section 3.1.3.1 (p7) |
| SOW-0250 | Develop Process Piping Line Designation Table (LDT) with required attributes | SOW Section 3.2.4.11 (p19) |

---
*Generated 2026-02-01 | SOW Refs: SOW-0117, SOW-0250*
