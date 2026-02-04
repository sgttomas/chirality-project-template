# Specification: Valve List (Piping)

## 1. Scope

### 1.1 Purpose
This specification defines the requirements for developing and maintaining the Valve List (VLL) for the Puget Sound Optimization Project at Sumas Tank Farm.

### 1.2 Applicability
- All new valves associated with booster pump installation
- Valves on modified existing piping
- Valves at tie-in connections to existing systems
- Valves for 5x6 manifold system
- Check valves, actuated valves, and manual isolation valves

### 1.3 Exclusions
- Instrument valves (covered under Instrumentation package)
- Vendor package internal valves (unless specified for Owner maintenance)
- Pressure safety valves (covered under Process Safety deliverables)

## 2. Requirements

### 2.1 Content Requirements
The Valve List shall include:

| Requirement | Description |
|-------------|-------------|
| REQ-01 | Unique valve tag number for each valve |
| REQ-02 | Associated line number |
| REQ-03 | Valve type (gate, globe, ball, check, plug, butterfly, etc.) |
| REQ-04 | Nominal valve size |
| REQ-05 | Pressure rating/class |
| REQ-06 | Material class designation |
| REQ-07 | End connection type (flanged, BW, SW, threaded) |
| REQ-08 | Operator type (manual, MOV, AOV, hydraulic) |
| REQ-09 | Fail position (if actuated) |
| REQ-10 | Service description |
| REQ-11 | P&ID reference |
| REQ-12 | Valve specification reference |
| REQ-13 | Quantity |

### 2.2 Format Requirements
- Excel spreadsheet format
- Sortable and filterable columns
- Version control and revision tracking
- Compatible with procurement and MTO extraction

### 2.3 Accuracy Requirements
- Valve tags shall match P&ID valve designations exactly
- Material classes shall be validated against PMC Index
- Actuator requirements shall match control system requirements

## 3. Standards

| Standard | Description |
|----------|-------------|
| ASME B16.34 | Valves - Flanged, Threaded, and Welding End (**ASSUMPTION**) |
| API 600 | Steel Gate Valves (**ASSUMPTION**) |
| API 602 | Steel Gate, Globe and Check Valves (**ASSUMPTION**) |
| API 608 | Metal Ball Valves (**ASSUMPTION**) |
| API 594 | Check Valves (**ASSUMPTION**) |
| MSS-SP-25 | Standard Marking System (**ASSUMPTION**) |
| TM-SPEC-VALVE-001 | TM Valve Specification (**TBD**) |
| TM-STD-VALVE-TAG | TM Valve Tagging Standard (**TBD**) |

## 4. Verification

### 4.1 Verification Methods
| Method | Description |
|--------|-------------|
| Review | Technical review by Lead Piping Engineer |
| Cross-check | Verification against P&IDs |
| Validation | PMC class validation |
| Audit | Document control audit for completeness |

### 4.2 Acceptance Criteria
- 100% of valves on P&IDs are captured in Valve List
- All mandatory fields populated
- No duplicate valve tags
- Actuator requirements verified against I&C requirements
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
- DEL-02.01: Line List
- DEL-02.19: Piping MTO
- DEL-02.20: Piping Specialty Items
- DEL-02.25: PMC Index

### 5.4 SOW Traceability
| SOW Item | Description | Reference |
|----------|-------------|-----------|
| SOW-0120 | Produce FEED valve list (VLL) | SOW Section 3.1.3.1 (p7-8) |
| SOW-0119 | Produce FEED mechanical/electrical datasheets for valves (incl check valves/actuators) | SOW Section 3.1.3.1 (p7) |

---
*Generated 2026-02-01 | SOW Refs: SOW-0119, SOW-0120*
