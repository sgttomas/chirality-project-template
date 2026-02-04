# Specification: DEL-01.04 Equipment Sizing Calculations

**Document ID:** DEL-01.04-SP
**Revision:** Phase 2.2 (PASS2-COMPLETE)
**Date:** 2026-02-01
**Status:** PASS2-COMPLETE

---

## Scope

### Purpose

This specification defines the requirements for Equipment Sizing Calculations for the Puget Sound Optimization (PSO) project at Sumas Tank Farm. These calculations support the sizing and selection of booster pumps, VFDs, flow meters, manifold headers, and associated equipment.

### Applicability

This specification applies to:
- FEED phase equipment sizing verification per SOW §2.3.1.6
- Detailed design phase equipment sizing finalization
- All process equipment within PKG-01 scope

### Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | 5 VS6 booster pumps, VFDs, flow meters, manifold, control valves, sump tank, reinjection pumps |
| Out of Scope | Electrical equipment sizing (PKG-06), structural sizing (PKG-04) |
| Out of Scope | Laurel Pump Station (explicitly excluded per SOW) |
| Interfaces | Coordination with DEL-01.05 (Line Sizing) and DEL-01.07 (Hydraulic Analysis) |

---

## Requirements

### Functional Requirements

| Req ID | Requirement | Priority | Source | Verification |
|--------|-------------|----------|--------|--------------|
| FR-01 | Calculations shall size equipment for peak flow rate of 315,000 bpd (2,100 m³/h) | Mandatory | SOW §2.2.1 | Calculation review |
| FR-02 | Calculations shall verify preliminary equipment sizing from existing engineering | Mandatory | SOW §2.3.1.6 | Calculation review |
| FR-03 | Calculations shall support pump configuration: 2 large, 2 small, 1 medium | Mandatory | SOW §2.3.1.2 | Calculation review |
| FR-04 | Calculations shall size VFDs for each booster pump (5 total) | Mandatory | SOW §2.3.1.4 | Calculation review |
| FR-05 | Calculations shall size discharge flow meters for each pump (5 total) | Mandatory | SOW §2.3.1.4 | Calculation review |
| FR-06 | Calculations shall support blending control (flow ratio) | Mandatory | SOW §2.3.1.4 | Calculation review |

### Content Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| CR-01 | Include design basis summary from DEL-01.01 (DBM) | Mandatory | Standard |
| CR-02 | Include hydraulic data from DEL-01.07 (Hydraulic Analysis) | Mandatory | Standard |
| CR-03 | Document all assumptions clearly | Mandatory | Standard |
| CR-04 | Include safety factors and design margins | Mandatory | Standard |
| CR-05 | Reference applicable codes and standards | Mandatory | Standard |
| CR-06 | Provide equipment selection recommendations | Mandatory | Standard |
| CR-07 | Include TBD tracking for incomplete inputs | Mandatory | Standard |

### Calculation Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| CAL-01 | Pump sizing: calculate required flow, head (TDH), NPSH, efficiency | Mandatory | API 610 |
| CAL-02 | VFD sizing: calculate motor power, speed range, turndown capability | Mandatory | Standard |
| CAL-03 | Flow meter sizing: calculate flow range, rangeability, accuracy requirements | Mandatory | Standard |
| CAL-04 | Manifold header sizing: calculate velocity, pressure drop | Mandatory | Standard |
| CAL-05 | Control valve sizing: calculate Cv, pressure drop (if applicable) | Mandatory | ISA 75.01 |
| CAL-06 | Sump tank sizing: calculate capacity per drainage requirements | Mandatory | SOW §3.2.3.10 |
| CAL-07 | Reinjection pump sizing: calculate flow and head per sump requirements | Mandatory | SOW §3.2.3.10 |

### Deliverable Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| DR-01 | Provide editable native files (Excel/MathCAD/Word) | Mandatory | SOW §3.2.3.18 |
| DR-02 | Provide PDF version for formal submission | Mandatory | SOW §4.3.5.1 |
| DR-03 | Follow TM document numbering conventions | Mandatory | SOW §4.3.4.1 |
| DR-04 | Register in Master Document Register (MDR) per DEL-00.01 | Mandatory | SOW §3.2.2.7 |

---

## Standards

### Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| API 610 | Centrifugal Pumps for Petroleum, Petrochemical and Natural Gas Industries | Pump sizing |
| HI 9.6 series | Hydraulic Institute Standards | Pump hydraulics |
| ISA 75.01 | Flow Equations for Sizing Control Valves | Control valve Cv |
| TMP Standards | Trans Mountain Standards | **TBD** - Attachment A08 |

### Design Criteria

| Criterion | Value | Source |
|-----------|-------|--------|
| Design Margin (Pumps) | **TBD** | **ASSUMPTION:** Typically 10-15% on head |
| Velocity Limit (Headers) | **TBD** | **ASSUMPTION:** Typically 3-5 m/s for liquid |
| NPSH Margin | **TBD** | **ASSUMPTION:** Minimum 1.0m above NPSHr |
| Flow Meter Rangeability | **TBD** | **ASSUMPTION:** Minimum 10:1 |

---

## Verification

### Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Calculation Review | Independent check of calculations | All calculations |
| Cross-Reference | Verify inputs against DEL-01.01 (DBM), DEL-01.07 (Hydraulic Analysis) | Input parameters |
| IDC Review | Interdisciplinary check | Mechanical, I&C coordination |
| TM Review | Client review | IFR/IFD/IFC milestones |

### Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All equipment sized for peak 315,000 bpd (2,100 m³/h) | Calculation review |
| AC-02 | Pump configuration supports 2L+2S+1M per SOW §2.3.1.2 | Calculation review |
| AC-03 | VFD and flow meter sized per pump (5 each) per SOW §2.3.1.4 | Calculation review |
| AC-04 | Inputs consistent with DEL-01.01 (DBM) | Cross-reference |
| AC-05 | Hydraulic data consistent with DEL-01.07 (Hydraulic Analysis) | Cross-reference |
| AC-06 | All assumptions documented | Documentation review |
| AC-07 | All TBDs resolved or flagged | TBD review |

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
| Equipment Sizing Calculation Report | PDF | 1 (plus revisions) |
| Native Calculation Files | Excel/MathCAD | 1 set per SOW §3.2.3.18 |
| Equipment Selection Summary | PDF/Excel | 1 |

### Records

| Record | Retention | Location |
|--------|-----------|----------|
| Calculation Report (all revisions) | Permanent | TM Document Control |
| Review Comments | Project duration + 7 years | Document Control |
| Approval Records | Project duration + 7 years | Document Control |

### Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Phase 2.2 | PASS2-COMPLETE - Cross-reference consistency check complete | 2026-02-01 |
| **TBD** | IFR submission | **TBD** |
| **TBD** | IFD submission | **TBD** |
| **TBD** | IFC submission | **TBD** |

---

*End of Specification*
