# Specification: DEL-01.03 Piping & Instrumentation Diagrams (P&IDs)

**Document ID:** DEL-01.03-SP
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Scope

### Purpose

This specification defines the requirements for Piping and Instrumentation Diagrams (P&IDs) for the Puget Sound Optimization (PSO) project at Sumas Tank Farm. P&IDs provide detailed schematic representation of process systems including all equipment, piping, instrumentation, and control systems.

### Applicability

This specification applies to:
- FEED phase P&ID development per SOW §3.1.3.1
- Detailed design phase P&ID updates through IFC per SOW §3.2.3.5
- All process systems within PKG-01 scope
- Vendor P&ID transformation to project standards per SOW §3.2.3.5

### Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | Booster pump station (5 VS6 pumps), 5x6 manifold system, sump/reinjection, associated auxiliaries |
| Out of Scope | Existing systems not modified by PSO (except tie-ins) |
| Out of Scope | Laurel Pump Station (explicitly excluded per SOW) |
| Interfaces | Battery limit tie-ins to existing Sumas Terminal facilities |

---

## Requirements

### Functional Requirements

| Req ID | Requirement | Priority | Source | Verification |
|--------|-------------|----------|--------|--------------|
| FR-01 | P&IDs shall depict all process equipment with correct tags | Mandatory | Standard | Review |
| FR-02 | P&IDs shall show all piping with line numbers and specifications | Mandatory | Standard | Review |
| FR-03 | P&IDs shall show all valves with correct types and tags | Mandatory | Standard | Review |
| FR-04 | P&IDs shall show all instrumentation with ISA 5.1 identification | Mandatory | ISA 5.1 | Review |
| FR-05 | P&IDs shall show control loops and interlocks | Mandatory | Standard | Review |
| FR-06 | P&IDs shall use TM-approved symbols, legends, and tagging | Mandatory | SOW §3.2.3.5 | Review |

### Content Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| CR-01 | Include all 5 booster pumps (VS6-type) with individual VFDs | Mandatory | SOW §2.3.1.1-2, §2.3.1.4 |
| CR-02 | Include discharge flow meters for each pump (5 total) | Mandatory | SOW §2.3.1.4 |
| CR-03 | Include 5x6 manifold header system (interpretation TBD with TM) | Mandatory | SOW §2.3.1.1 |
| CR-04 | Include blending control instrumentation | Mandatory | SOW §2.3.1.4 |
| CR-05 | Include sump tank and reinjection pumps | Mandatory | SOW §3.2.3.10 |
| CR-06 | Transform vendor P&IDs to project format (TM symbols/legends/tagging) | Mandatory | SOW §3.2.3.5 |
| CR-07 | Develop auxiliary system P&IDs as needed | Mandatory | SOW §3.2.3.6 |
| CR-11 | Coordinate line numbers with DEL-02.01 (Line List) | Mandatory | Standard practice |
| CR-12 | Coordinate valve tags with DEL-02.02 (Valve List) | Mandatory | Standard practice |
| CR-13 | Coordinate instrument tags with DEL-07.02 (Instrument Index) | Mandatory | Standard practice |
| CR-08 | Include equipment ratings and capacities | Mandatory | Standard |
| CR-09 | Include line specifications and insulation | Mandatory | Standard |
| CR-10 | Include battery limits and tie-in identifications | Mandatory | Standard |

### Drawing Requirements

| Req ID | Requirement | Acceptance Criteria |
|--------|-------------|---------------------|
| DR-01 | Drawing shall be legible at D-size (or TM standard) | Visual inspection |
| DR-02 | Symbols shall comply with TM standards | Symbol check |
| DR-03 | Text shall be minimum 2.5mm height | Measurement |
| DR-04 | Drawing shall include revision history | Review |
| DR-05 | Line numbers shall be unique and traceable to DEL-02.01 (Line List) | Cross-reference check |
| DR-06 | Instrument tags shall be unique and traceable to DEL-07.02 (Instrument Index) | Cross-reference check |
| DR-08 | Valve tags shall be unique and traceable to DEL-02.02 (Valve List) | Cross-reference check |
| DR-07 | Native CAD files shall be submitted | Per SOW §3.2.3.18 |

### Integration Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| IR-01 | P&IDs shall incorporate HAZOP findings per DEL-01.15 | Mandatory | SOW §3.2.2.1, §3.2.3.4 |
| IR-02 | P&IDs shall incorporate model review findings | Mandatory | SOW §3.2.3.4 |
| IR-03 | P&IDs shall incorporate change notices | Mandatory | SOW §3.2.3.4 |
| IR-04 | P&IDs shall incorporate vendor data updates | Mandatory | SOW §3.2.3.4 |

---

## Standards

### Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| ISA 5.1 | Instrumentation Symbols and Identification | Symbol standards |
| TM-**TBD** | Trans Mountain P&ID Standards | Symbols/legends/tagging per SOW §3.2.3.5 |
| TM-**TBD** | Trans Mountain Drawing Standards | Drawing format |
| TM-**TBD** | Trans Mountain CAD Standards | CAD requirements |

### Symbol Requirements

| Item | Standard | Notes |
|------|----------|-------|
| Pumps | TM Standard / ISA | VS6-type centrifugal |
| Valves | TM Standard / ISA | Block, control, check, relief, etc. |
| Instrumentation | ISA 5.1 | Full instrument identification |
| Piping | TM Standard | Line type, specifications |
| Control Logic | ISA 5.1 | Control loops, interlocks, ESD |
| VFDs | TM Standard | Variable frequency drive symbol |

### Tagging Requirements

| Element | Convention | Notes |
|---------|------------|-------|
| Equipment | Per TM numbering system | **TBD** - Confirm with TM |
| Instruments | ISA 5.1 + TM conventions | **TBD** |
| Lines | Per TM line numbering | Align with DEL-02.01 |
| Valves | Per TM valve numbering | Align with DEL-02.02 |

---

## Verification

### Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Drawing Review | Check against checklist | All requirements |
| Symbol Check | Verify TM compliance | Symbol requirements |
| Cross-Reference | Check consistency with DEL-02.01 (Line List), DEL-02.02 (Valve List), DEL-07.02 (Instrument Index) | Tag/number consistency |
| IDC Review | Interdisciplinary check | Interfaces |
| HAZOP Review | Verify all findings incorporated | HAZOP action items per DEL-01.15 |

### Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All equipment shown with correct tags (5 VS6 pumps, 5 VFDs, 5 flow meters, 5x6 manifold) | Drawing review |
| AC-02 | All piping shown with line numbers per DEL-02.01 | Drawing review |
| AC-03 | All instrumentation per ISA 5.1 and DEL-07.02 | Symbol check |
| AC-04 | Symbols per TM standards | Symbol check |
| AC-05 | Title block complete and accurate | Drawing review |
| AC-06 | HAZOP markups incorporated (IFC stage) per DEL-01.15 | Review per SOW §3.2.3.4 |
| AC-07 | Vendor P&IDs transformed per SOW §3.2.3.5 (TM symbols/legends/tagging) | Drawing review |
| AC-08 | Consistent with Line List (DEL-02.01) | Cross-reference |
| AC-09 | Consistent with Valve List (DEL-02.02) | Cross-reference |
| AC-10 | Consistent with Instrument Index (DEL-07.02) | Cross-reference |

### Review Stages

| Stage | Milestone | Reviewer | Source |
|-------|-----------|----------|--------|
| IFR | FEED submission | Engineering Lead + TM | SOW §3.1.2.2 |
| IFD | FEED completion | TM Review | SOW §3.1.2.2 |
| IFC | Detailed Design completion | TM Approval | SOW §3.2.3.5 |

---

## Documentation

### Deliverable Documentation

| Document | Format | Quantity |
|----------|--------|----------|
| P&ID Drawing Set | PDF | 1 set (all sheets) |
| CAD Native Files | dwg/dgn | 1 set per SOW §3.2.3.18 |
| Legend/Symbol Sheet | PDF + CAD | 1 |

### Records

| Record | Retention | Location |
|--------|-----------|----------|
| Review Comments | Project duration + 7 years | Document Control |
| Revision History | Within drawing | Drawing set |
| HAZOP Markups | Project duration + 7 years | Document Control |
| Vendor P&ID Source Files | Project duration + 7 years | Document Control |

### Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Phase 2.2 | INITIALIZED - Documents generated | 2026-02-01 |
| **TBD** | IFR submission | **TBD** |
| **TBD** | IFD submission | **TBD** |
| **TBD** | IFC submission | **TBD** |

---

*End of Specification*
