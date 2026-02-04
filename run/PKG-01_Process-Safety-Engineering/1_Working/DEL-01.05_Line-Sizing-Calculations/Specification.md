# Specification: DEL-01.05 Line Sizing Calculations

**Document ID:** DEL-01.05-SP
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Scope

### Purpose

This specification defines the requirements for Line Sizing Calculations for the Puget Sound Optimization (PSO) project at Sumas Tank Farm. These calculations support the sizing of process piping for the booster pump station, manifold headers, and associated systems.

### Applicability

This specification applies to:
- FEED phase line sizing per SOW-0114
- Detailed design phase optimization per SOW-0130
- All process piping within PKG-01 scope

### Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | Tank suction, manifold headers (5x6), pump suction/discharge, blending lines, auxiliaries |
| Out of Scope | Existing piping not modified by PSO (except tie-ins) |
| Out of Scope | Laurel Pump Station (explicitly excluded per SOW) |
| Interfaces | Coordination with DEL-01.04 (Equipment Sizing) and DEL-01.07 (Hydraulic Analysis) |

---

## Requirements

### Functional Requirements

| Req ID | Requirement | Priority | Source | Verification |
|--------|-------------|----------|--------|--------------|
| FR-01 | Calculations shall size lines for peak flow rate of 315,000 bpd (2,100 m³/h) | Mandatory | SOW §2.2.1 | Calculation review |
| FR-02 | Calculations shall support hydraulic optimization per SOW-0130 | Mandatory | SOW-0130 | Calculation review |
| FR-03 | Calculations shall support 5x6 manifold configuration (5 inlet headers, 6 outlet headers) | Mandatory | SOW §2.3.1.1 | Calculation review |
| FR-04 | Calculations shall support 5 booster pump suction/discharge lines | Mandatory | SOW §2.3.1.1 | Calculation review |
| FR-05 | Calculations shall support blending line requirements | Mandatory | SOW §2.3.1.4 | Calculation review |

### Content Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| CR-01 | Include design basis summary from DEL-01.01 | Mandatory | Standard |
| CR-02 | Include hydraulic data from DEL-01.07 | Mandatory | Standard |
| CR-03 | Document all assumptions clearly | Mandatory | Standard |
| CR-04 | Include velocity calculations for all lines | Mandatory | Standard |
| CR-05 | Include pressure drop calculations | Mandatory | Standard |
| CR-06 | Reference applicable codes and standards | Mandatory | CSA Z662, ASME B31.4 |
| CR-07 | Include TBD tracking for incomplete inputs | Mandatory | Standard |
| CR-08 | Support Line List (DEL-02.01) development | Mandatory | Standard |

### Calculation Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| CAL-01 | Calculate velocity for all line categories | Mandatory | Standard |
| CAL-02 | Verify velocity within allowable limits | Mandatory | Standard |
| CAL-03 | Calculate pressure drop for critical lines | Mandatory | Standard |
| CAL-04 | Determine pipe class per service and P/T | Mandatory | TMP Standards (Attachment A08) |
| CAL-05 | Size manifold headers for 5x6 configuration (5 inlet, 6 outlet) | Mandatory | SOW §2.3.1.1 |

### Deliverable Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| DR-01 | Provide editable native files (Excel/MathCAD) | Mandatory | SOW-0231 |
| DR-02 | Provide PDF version for formal submission | Mandatory | SOW §4.3.5.1 |
| DR-03 | Follow TM document numbering conventions | Mandatory | SOW §4.3.4.1 |
| DR-04 | Register in Master Document Register (MDR) | Mandatory | DEL-00.01 |

---

## Standards

### Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems | Primary piping code |
| ASME B31.4 | Pipeline Transportation Systems for Liquids | Liquid piping |
| API RP 14E | Erosional velocity limits | Velocity criteria reference |
| TMP Standards | Trans Mountain Standards | **TBD** - Attachment A08 |

### Design Criteria

| Criterion | Suction | Discharge | Headers | Source |
|-----------|---------|-----------|---------|--------|
| Velocity (max) | **TBD** | **TBD** | **TBD** | **ASSUMPTION:** 1.0-2.0 m/s suction, 3.0-5.0 m/s discharge |
| Erosional Velocity | **TBD** | **TBD** | **TBD** | Per API RP 14E or TMP Standards |
| Pressure Drop | **TBD** | **TBD** | **TBD** | Per hydraulic optimization (DEL-01.07) |

---

## Verification

### Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Calculation Review | Independent check of calculations | All calculations |
| Cross-Reference | Verify inputs against DEL-01.01, DEL-01.07 | Input parameters |
| IDC Review | Interdisciplinary check | Piping (PKG-02) coordination |
| TM Review | Client review | IFR/IFD/IFC milestones |

### Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All lines sized for peak 315,000 bpd | Calculation review |
| AC-02 | Velocities within allowable limits | Calculation review |
| AC-03 | Pressure drops within hydraulic budget | Cross-reference DEL-01.07 |
| AC-04 | Inputs consistent with DEL-01.01 (DBM) | Cross-reference |
| AC-05 | Hydraulic data consistent with DEL-01.07 | Cross-reference |
| AC-06 | Manifold sized for 5x6 configuration (5 inlet, 6 outlet) | Calculation review |
| AC-07 | All assumptions documented | Documentation review |
| AC-08 | All TBDs resolved or flagged | TBD review |

### Review Stages

| Stage | Milestone | Reviewer | Source |
|-------|-----------|----------|--------|
| IFR | FEED submission | Engineering Lead + TM | SOW §3.1.2.2 |
| IFD | FEED completion | TM Review | SOW §3.1.2.2 |
| IFC | Detailed Design completion | TM Approval | SOW §3.2.2.2 |

---

## Documentation

### Deliverable Documentation

| Document | Format | Quantity |
|----------|--------|----------|
| Line Sizing Calculation Report | PDF | 1 (plus revisions) |
| Native Calculation Files | Excel/MathCAD | 1 set per SOW-0231 |
| Line Size Summary Table | PDF/Excel | 1 |

### Records

| Record | Retention | Location |
|--------|-----------|----------|
| Calculation Report (all revisions) | Permanent | TM Document Control |
| Review Comments | Project duration + 7 years | Document Control |
| Approval Records | Project duration + 7 years | Document Control |

### Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Phase 2.2 | INITIALIZED - Documents generated | 2026-02-01 |
| **TBD** | IFR submission | **TBD** |
| **TBD** | IFD submission | **TBD** |
| **TBD** | IFC submission | **TBD** |

---

*End of Specification*
