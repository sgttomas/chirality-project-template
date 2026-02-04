# Specification: Piping Material Takeoff (MTO)

**Deliverable ID:** DEL-02.19
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This specification defines the requirements for developing the Piping Material Takeoff (MTO) for the Puget Sound Optimization Project (PSO) at Sumas Tank Farm. The MTO shall provide a comprehensive list of all piping materials required for procurement, fabrication, and construction.

---

## 2. Scope

### 2.1 Applicable Facilities
- New booster pump station (5 x VS6-type booster pumps) at SW corner of TK-102
- New 5x6 manifold system
- Associated infrastructure piping and connections
- Tie-ins to existing systems

### 2.2 Material Categories
The MTO shall include the following material categories:

| Category | Sub-Categories |
|----------|----------------|
| Piping | Line pipe, nipples, swages |
| Fittings | Buttweld, socketweld, threaded, flanged |
| Flanges | Weld neck, slip-on, blind, spectacle blind, spacer |
| Valves | Gate, globe, ball, check, plug, butterfly, control, safety |
| Specialty Items | Strainers, Y-strainers, filters, expansion joints |
| Bolting | Stud bolts, machine bolts, nuts, washers |
| Gaskets | Spiral wound, ring joint, sheet, kammprofile |
| Supports | Fabricated supports, shoes, clamps, spring hangers |

---

## 3. Normative References

### 3.1 Codes and Standards (Mandatory)

| Code/Standard | Title | Application |
|---------------|-------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems | Primary code per SOW |
| ASME B31.4 | Pipeline Transportation Systems | Supplemental code |
| MSS SP-43 | Wrought and Fabricated Butt-Welding Fittings | Fitting dimensions |
| ASME B16.5 | Pipe Flanges and Flanged Fittings | Flange standards |
| ASME B16.34 | Valves - Flanged, Threaded, and Welding End | Valve standards |

### 3.2 Project References

| Reference | Description |
|-----------|-------------|
| TM Standards and Specifications | Per SOW Section 4.1.2 |
| Piping Material Class Index | DEL-02.25 |
| Valve List | DEL-02.02 |
| Piping Isometrics | DEL-02.13 |
| Specialty Item Datasheets | DEL-02.20 |
| Line Designation Table | DEL-02.18 |

---

## 4. Technical Requirements

### 4.1 General Requirements

4.1.1 The MTO shall include all piping materials required for the PSO scope.

4.1.2 Materials shall be organized by commodity type and piping class.

4.1.3 All materials shall reference applicable specifications per PMC Index.

4.1.4 Quantities shall be based on latest approved design documents.

4.1.5 The MTO shall be delivered in editable native format (Excel).

### 4.2 Data Field Requirements

Each material line item shall include:

| Field | Description | Mandatory |
|-------|-------------|-----------|
| Item Number | Sequential or commodity-based | Yes |
| Commodity Code | TM commodity classification | Yes |
| Description | Full material description | Yes |
| Size | Nominal pipe size | Yes |
| Rating | Pressure class/schedule | Yes |
| Material | ASTM/API specification | Yes |
| Piping Class | Per PMC Index | Yes |
| Unit | EA, M, KG, etc. | Yes |
| Quantity | Required amount | Yes |
| Unit Weight | Weight per unit | Optional |
| Total Weight | Extended weight | Optional |
| Unit Price | Estimated cost | Optional |
| Extended Price | Total cost | Optional |
| Remarks | Special notes | Optional |

### 4.3 Quantity Derivation

| Material Type | Primary Source | Secondary Source |
|---------------|----------------|------------------|
| Pipe | 3D model extraction | Isometric BOMs |
| Fittings | 3D model extraction | Isometric BOMs |
| Flanges | 3D model extraction | Equipment/Valve connections |
| Valves | Valve List (DEL-02.02) | P&IDs |
| Specialty Items | Specialty Datasheets (DEL-02.20) | P&IDs |
| Bolting | Flange count x bolt requirement | PMC bolt lists |
| Gaskets | Flange count | PMC gasket lists |
| Supports | Support location plans | Stress analysis output |

### 4.4 Quantity Allowances

| Phase | Piping | Fittings | Valves | Bolting | Gaskets |
|-------|--------|----------|--------|---------|---------|
| FEED | +15% | +20% | 0% | +10% | +10% |
| IFD | +10% | +15% | 0% | +5% | +5% |
| IFC | +5% | +10% | 0% | +5% | +5% |

ASSUMPTION: Allowances per industry practice - to be confirmed with TM.

### 4.5 Material Specifications

4.5.1 All materials shall be specified per approved Piping Material Classes (DEL-02.25).

4.5.2 Specifications shall include:
- ASTM/API material designation
- Grade and heat treatment
- Dimensional standard
- End connections
- Pressure-temperature rating

4.5.3 Non-standard materials shall be flagged for special procurement.

---

## 5. Format and Presentation

### 5.1 File Format

| Requirement | Specification |
|-------------|---------------|
| Primary Format | Microsoft Excel (.xlsx) |
| Secondary Format | PDF for distribution |
| Compatibility | Excel 2016 or later |

### 5.2 Workbook Structure

| Sheet | Content |
|-------|---------|
| Cover | Document identification, revision history |
| Summary | Total quantities by commodity |
| Pipe | Pipe materials by size and class |
| Fittings | Fitting materials |
| Flanges | Flange materials |
| Valves | Valve materials |
| Specialty | Specialty items |
| Bolting | Bolting materials |
| Gaskets | Gasket materials |
| Supports | Support materials |
| Legend | Abbreviations and codes |

### 5.3 Reporting Levels

| Level | Content |
|-------|---------|
| Summary | Total by commodity type |
| By Class | Subtotals by piping class |
| By Line | Quantities per line number (optional) |
| By Area | Quantities per plant area (optional) |
| Detail | Individual line items |

---

## 6. Interface Requirements

### 6.1 Upstream Interfaces (Inputs)

| Source | Data Provided |
|--------|---------------|
| DEL-02.13 (Isometrics) | Pipe and fitting quantities |
| DEL-02.02 (Valve List) | Valve quantities |
| DEL-02.20 (Specialty Datasheets) | Specialty item requirements |
| DEL-02.25 (PMC Index) | Material specifications |
| DEL-02.16 (Support Drawings) | Support material quantities |
| DEL-02.28 (3D Model) | Model-based quantities |

### 6.2 Downstream Interfaces (Outputs)

| Consumer | Data Used |
|----------|-----------|
| Cost Estimate | Material costs |
| Procurement | Purchase requisitions |
| Construction | Material requirements |
| Fabrication | Spool material lists |

---

## 7. Quality Assurance

### 7.1 Quantity Verification

- Compare MTO quantities against isometric BOMs
- Verify valve count against Valve List
- Reconcile specialty items against datasheets
- Cross-check with 3D model reports

### 7.2 Specification Verification

- Validate material specs against PMC Index
- Verify flange ratings match service conditions
- Check valve specifications against datasheets

### 7.3 Completeness Verification

- All piping classes covered
- All areas/systems included
- No missing categories

---

## 8. Deliverables

| Item | Format | Quantity |
|------|--------|----------|
| Piping MTO | Excel (.xlsx) | 1 (native) |
| Piping MTO | PDF | 1 (for distribution) |
| Summary Report | PDF | 1 |
| Transmittal | Per TM requirements | Per submission |

---

## 9. TBD Items

| Item | Description | Owner |
|------|-------------|-------|
| TBD-01 | TM MTO template format | TM Procurement |
| TBD-02 | Commodity coding system | TM |
| TBD-03 | Pricing requirements | TM Project Controls |
| TBD-04 | Allowance percentages | TM |
| TBD-05 | Weight reporting requirements | TM |

---

## 10. Source References

| Reference | Document | Section |
|-----------|----------|---------|
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.1.3.1 (p8) |
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.9 (p19) |
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.12 (p20) |
| Decomposition | PSO Decomposition REVISED v2 | DEL-02.19, SOW-0127, SOW-0248, SOW-0251 |

---

*Specification generated as initial draft. All TBD items require resolution during FEED/Detailed Design phases.*
