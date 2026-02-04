# Specification: DEL-01.10 Valve Numbering Diagrams

**Document ID:** DEL-01.10-SP
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for Valve Numbering Diagrams for the Puget Sound Optimization (PSO) project. These diagrams shall provide a clear schematic representation of all valves within the project scope, showing unique tag numbers and valve locations within the process systems.

### 1.2 Applicability

This specification applies to:
- FEED phase preliminary valve numbering diagrams
- Detailed design phase updates incorporating HAZOP, model review, change notices, and vendor data (per SOW-0222)
- All valves within PKG-01 process scope
- Maintenance through IFC (per SOW-0232)

### 1.3 Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | Valve numbering diagram development and maintenance, valve tag assignment |
| Out of Scope | Detailed valve specifications (PKG-02/03), Valve list (DEL-02.02 in PKG-02), Piping layouts (DEL-02.12 in PKG-02) |

---

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Verification |
|--------|-------------|----------|--------------|
| FR-01 | Diagrams shall show all valves with unique tag numbers | Mandatory | Review |
| FR-02 | Valve tag numbers shall follow TM numbering convention | Mandatory | Review |
| FR-03 | Diagrams shall show valve locations relative to major equipment | Mandatory | Review |
| FR-04 | Diagrams shall include line numbers for all associated piping | Mandatory | Review |
| FR-05 | Diagrams shall include P&ID cross-references (DEL-01.03) | Mandatory | Review |
| FR-06 | Diagrams shall be updated per HAZOP findings (DEL-01.15) | Mandatory | HAZOP tracking |
| FR-07 | Diagrams shall include all relief valves per DEL-01.06 | Mandatory | Review |
| FR-08 | Diagrams shall be consistent with valve list (DEL-02.02) | Mandatory | Cross-check |

### 2.2 Content Requirements

| Req ID | Requirement | Priority |
|--------|-------------|----------|
| CR-01 | Include title block with drawing number, revision, date | Mandatory |
| CR-02 | Include system/area identification | Mandatory |
| CR-03 | Include all valve symbols per legend | Mandatory |
| CR-04 | Include valve tag numbers (unique) | Mandatory |
| CR-05 | Include line numbers | Mandatory |
| CR-06 | Include major equipment references | Mandatory |
| CR-07 | Include flow direction arrows | Mandatory |
| CR-08 | Include legend for all symbols used | Mandatory |
| CR-09 | Include P&ID cross-references | Mandatory |
| CR-10 | Include revision history | Mandatory |

### 2.3 Performance Requirements

| Req ID | Requirement | Acceptance Criteria |
|--------|-------------|---------------------|
| PR-01 | Diagrams shall enable valve identification in field | Clear, legible tag numbers |
| PR-02 | Diagrams shall be consistent with P&IDs (DEL-01.03) | 100% tag number correlation |
| PR-03 | Diagrams shall be consistent with Valve List (DEL-02.02) | 100% valve inventory match |

---

## 3. Standards

### 3.1 Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| ISA 5.1 | Instrumentation Symbols and Identification | Valve symbol standards |
| TM Drawing Standards | Trans Mountain Drawing Requirements | Format, title block |
| TM Tag Numbering Convention | Trans Mountain Tagging Convention | Valve numbering format |
| TM Symbol Library | Trans Mountain Symbols | Project-specific symbols |

### 3.2 Drawing Requirements

| Requirement | Specification | Notes |
|-------------|---------------|-------|
| Drawing Size | **TBD** | **ASSUMPTION:** D-size typical |
| CAD Format | AutoCAD/MicroStation | Per TM requirements |
| Scale | Not to scale (schematic) | Standard practice |
| Title Block | TM standard | Per TM template |
| Numbering | Per TM convention | **TBD** |

---

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| P&ID Cross-check | Verify against P&IDs (DEL-01.03) for completeness | All valves |
| Valve List Cross-check | Verify against valve list (DEL-02.02 in PKG-02) | All valves |
| Relief System Cross-check | Verify relief valves against DEL-01.06 | Relief valves |
| Drawing Review | Review for drafting standards | All drawings |
| HAZOP Tracking | Verify HAZOP (DEL-01.15) changes incorporated | Updates |

### 4.2 Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All valves from P&IDs (DEL-01.03) included | P&ID comparison |
| AC-02 | Tag numbers unique and per TM convention | Tag audit |
| AC-03 | Line numbers consistent with P&IDs | Cross-check |
| AC-04 | Drawing format per TM standards | TM review |
| AC-05 | HAZOP (DEL-01.15) findings incorporated | HAZOP action tracking |
| AC-06 | Relief valves per DEL-01.06 included | Relief system cross-check |
| AC-07 | Valve list (DEL-02.02) reconciled | Inventory comparison |
| AC-08 | TM approval obtained | Sign-off |

### 4.3 Review Stages

| Stage | Milestone | Reviewer |
|-------|-----------|----------|
| IFR | FEED submission | Engineering Lead |
| IFD | FEED completion | TM Review |
| IFC | Detailed Design completion per SOW-0222, SOW-0232 | TM Approval |

---

## 5. Documentation

### 5.1 Deliverable Documentation

| Document | Format | Quantity |
|----------|--------|----------|
| Valve Numbering Diagrams | PDF | As required |
| Native CAD Files | dwg/dgn | 1 set |
| Valve Tag Register | Excel | 1 (cross-reference) |

### 5.2 Records

| Record | Retention | Location |
|--------|-----------|----------|
| Review Comments | Project duration + 7 years | Document Control |
| Revision History | Permanent | Within drawing |
| HAZOP Action Records | Project duration + 7 years | Document Control |

### 5.3 Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Pass 1 | Initial draft generation | 2026-02-01 |
| Pass 2 | Cross-reference consistency check | 2026-02-01 |
| **TBD** | IFR submission | **TBD** |
| **TBD** | IFD submission | **TBD** |
| **TBD** | IFC submission per SOW-0232 | **TBD** |

---

*End of Specification*
