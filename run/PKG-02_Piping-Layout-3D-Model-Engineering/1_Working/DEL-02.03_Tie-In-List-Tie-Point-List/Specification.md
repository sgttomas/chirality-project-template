# Specification: Tie-In List / Tie Point List

## 1. Scope

### 1.1 Purpose
This specification defines the requirements for developing and maintaining the Tie-In List for the Puget Sound Optimization Project at Sumas Tank Farm.

### 1.2 Applicability
- All connections between new piping and existing Sumas Tank Farm systems
- Connections between new booster pump piping and existing tank systems
- Manifold connections to existing headers
- Utility tie-ins (if within piping scope)

### 1.3 Exclusions
- Hot tap execution procedures (by others per SOW)
- Tie-in execution activities (by others per SOW)
- Instrument connections (covered under Instrumentation package)

## 2. Requirements

### 2.1 Content Requirements
The Tie-In List shall include:

| Requirement | Description |
|-------------|-------------|
| REQ-01 | Unique tie-in number for each connection point |
| REQ-02 | New line number being connected |
| REQ-03 | Existing line/equipment identifier |
| REQ-04 | Tie-in description |
| REQ-05 | P&ID reference(s) |
| REQ-06 | Connection size and rating |
| REQ-07 | Connection type (flanged, welded, hot tap) |
| REQ-08 | Physical location and coordinates |
| REQ-09 | Isolation requirements |
| REQ-10 | Execution method (cold cut, hot tap, etc.) |
| REQ-11 | Shutdown requirements (Yes/No, duration) |
| REQ-12 | Priority/sequence recommendation |

### 2.2 Format Requirements
- Excel spreadsheet format
- Sortable and filterable columns
- Version control and revision tracking
- Coordinates compatible with site survey data

### 2.3 Accuracy Requirements
- Tie-in locations shall be verified against existing as-built drawings
- Coordinates shall be verified by field survey where possible
- Isolation requirements shall be reviewed by Operations

## 3. Standards

| Standard | Description |
|----------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems (**ASSUMPTION**) |
| ASME B31.3 | Process Piping (**ASSUMPTION**) |
| TM-PROC-TIE-001 | TM Tie-In Procedure (**TBD**) |
| TM-STD-TIE-NUM | TM Tie-In Numbering Standard (**TBD**) |

## 4. Verification

### 4.1 Verification Methods
| Method | Description |
|--------|-------------|
| Review | Technical review by Lead Piping Engineer |
| Field Verification | Site walkdown to verify existing conditions |
| Cross-check | Verification against P&IDs and existing drawings |
| Operations Review | Review by TM Operations for isolation/shutdown |

### 4.2 Acceptance Criteria
- All tie-in points identified on P&IDs are captured
- All mandatory fields populated
- No duplicate tie-in numbers
- Location coordinates verified
- Isolation requirements approved by Operations
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
- DEL-02.04: Piping Key Plan
- DEL-02.05: Piping Site Plan
- Existing Sumas Tank Farm drawings (TM-provided)

### 5.4 SOW Traceability
| SOW Item | Description | Reference |
|----------|-------------|-----------|
| SOW-0121 | Produce FEED tie-in list (TIL) | SOW Section 3.1.3.1 (p7-8) |
| SOW-0249 | Develop piping tie-in table (line number, tie-in description, P&ID number, tie-in number); hot taps and other tie-in activities excluded (by others) | SOW Section 3.2.4.10 (p19) |

---
*Generated 2026-02-01 | SOW Refs: SOW-0121, SOW-0249*
