# Specification: DEL-01.02 Process Flow Diagrams (PFDs)

**Document ID:** DEL-01.02-SP
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Scope

### Purpose

This specification defines the requirements for Process Flow Diagrams (PFDs) for the Puget Sound Optimization (PSO) project at Sumas Tank Farm. PFDs provide a high-level schematic representation of the process systems, showing major equipment, flow paths, and operating conditions.

### Applicability

This specification applies to:
- FEED phase PFD development
- Detailed design phase PFD updates through IFC
- All process systems within PKG-01 scope
- Booster pump station, manifold system, and blending control systems

### Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | All new and modified process systems: 5 VS6 booster pumps (2 Large + 2 Small + 1 Medium), 5x6 manifold, blending system |
| Out of Scope | Existing systems not affected by PSO modifications |
| Out of Scope | Laurel Pump Station (explicitly excluded per SOW) |
| Interfaces | Battery limit tie-ins to existing Sumas Terminal facilities |

---

## Requirements

### Functional Requirements

| Req ID | Requirement | Priority | Source | Verification |
|--------|-------------|----------|--------|--------------|
| FR-01 | PFDs shall depict all major equipment in the process | Mandatory | Standard | Review |
| FR-02 | PFDs shall show process flow paths and directions | Mandatory | Standard | Review |
| FR-03 | PFDs shall include heat and material balance data | Mandatory | Standard | Review |
| FR-04 | PFDs shall identify battery limits | Mandatory | Standard | Review |
| FR-05 | PFDs shall use TM-approved symbols and legends | Mandatory | TM Standards | Review |
| FR-06 | PFDs shall show both sustainable (275,000 bpd / 1,822 m³/h) and peak (315,000 bpd / 2,100 m³/h) flow cases | Mandatory | SOW §2.2.1 | Review |
| FR-07 | PFDs shall show 5 VS6 booster pumps (2 Large + 2 Small + 1 Medium) with VFD and flow meter indications | Mandatory | SOW §2.3.1.1-4 | Review |
| FR-08 | PFDs shall show 5x6 manifold configuration | Mandatory | SOW §2.3.1.1 | Review |

### Content Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| CR-01 | Include stream numbers for all process streams | Mandatory | Standard |
| CR-02 | Show design pressure and temperature for streams per DEL-01.01 DBM | Mandatory | Standard |
| CR-03 | Show normal operating and design flow rates | Mandatory | Standard |
| CR-04 | Include equipment tag numbers per TM convention | Mandatory | TM Standards |
| CR-05 | Show major control loops (simplified) - blending ratio control | Mandatory | SOW §2.3.1.4 |
| CR-06 | Include drawing title block per TM format | Mandatory | TM Standards |
| CR-07 | Reference Appendix B PFD as input basis | Mandatory | Available input |

### Drawing Requirements

| Req ID | Requirement | Acceptance Criteria |
|--------|-------------|---------------------|
| DR-01 | Drawing shall be legible at D-size (or TM standard) | Visual inspection |
| DR-02 | Symbols shall comply with TM standards | Symbol check |
| DR-03 | Text shall be minimum 2.5mm height | Measurement |
| DR-04 | Drawing shall include revision history | Review |
| DR-05 | Native CAD files shall be submitted | Per SOW §3.2.3.18 |

---

## Standards

### Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| ISA 5.1 | Instrumentation Symbols and Identification | Symbol standards |
| TM-**TBD** | Trans Mountain Drawing Standards | Drawing format |
| TM-**TBD** | Trans Mountain CAD Standards | CAD requirements |

### Symbol Requirements

| Item | Standard | Notes |
|------|----------|-------|
| Pumps | TM Standard / ISA | VS6-type centrifugal |
| Valves | TM Standard / ISA | Block, control, check, relief |
| Instrumentation | ISA 5.1 | Basic loops only on PFD |
| Piping | TM Standard | Line type, arrows |
| VFDs | TM Standard | Variable frequency drive indication |

---

## Verification

### Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Drawing Review | Check against checklist | All requirements |
| Symbol Check | Verify TM compliance | Symbol requirements |
| Data Verification | Cross-check with DEL-01.01 DBM and DEL-01.07 Hydraulic Analysis | H&MB data |
| IDC Review | Interdisciplinary check | Interfaces |

### Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All equipment shown with correct tags (5 pumps: 2 Large + 2 Small + 1 Medium, manifold) | Drawing review |
| AC-02 | Stream data consistent with DEL-01.01 DBM and DEL-01.07 Hydraulic Analysis | Data verification |
| AC-03 | Symbols per TM standards | Symbol check |
| AC-04 | Title block complete and accurate | Drawing review |
| AC-05 | HAZOP markups incorporated (IFC) | Review per SOW §3.2.3.14 |
| AC-06 | Consistent with input PFD (Appendix B) | Cross-reference |

### Review Stages

| Stage | Milestone | Reviewer | Source |
|-------|-----------|----------|--------|
| IFR | FEED submission | Engineering Lead + TM | SOW §3.1.2.2 |
| IFD | FEED completion | TM Review | SOW §3.1.2.2 |
| IFC | Detailed Design completion | TM Approval | SOW §3.2.3.14 |

---

## Documentation

### Deliverable Documentation

| Document | Format | Quantity |
|----------|--------|----------|
| PFD Drawing Set | PDF | 1 set (all sheets) |
| CAD Native Files | dwg/dgn | 1 set per SOW §3.2.3.18 |
| Stream Data Table | Excel | 1 (if separate from drawing) |

### Records

| Record | Retention | Location |
|--------|-----------|----------|
| Review Comments | Project duration + 7 years | Document Control |
| Revision History | Within drawing | Drawing set |
| HAZOP Markups | Project duration + 7 years | Document Control |

### Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Phase 2.2 | INITIALIZED - Documents generated | 2026-02-01 |
| **TBD** | IFR submission | **TBD** |
| **TBD** | IFD submission | **TBD** |
| **TBD** | IFC submission | **TBD** |

---

*End of Specification*
