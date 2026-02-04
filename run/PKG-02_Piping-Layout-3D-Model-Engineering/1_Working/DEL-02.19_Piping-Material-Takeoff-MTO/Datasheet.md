# Datasheet: Piping Material Takeoff (MTO)

**Deliverable ID:** DEL-02.19
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Document Identification

| Field | Value |
|-------|-------|
| Document Number | TBD (per TM document numbering system) |
| Document Title | Piping Material Takeoff (MTO) |
| Revision | A (IFR) |
| Discipline | Piping |
| Project | Puget Sound Optimization Project (PSO) |
| Facility | Sumas Tank Farm (Sumas Terminal) |

---

## 2. Deliverable Summary

| Attribute | Value |
|-----------|-------|
| Deliverable Type | List |
| Primary Output | Piping MTO |
| Responsible Party | Engineering Contractor |
| Phase Coverage | FEED + Detailed Design |
| Final Status Target | IFC (Issued for Construction) |

---

## 3. Scope Definition

### 3.1 Included Scope
- Material takeoff for all piping components within PSO scope
- Valves (manual and actuated)
- Fittings (elbows, tees, reducers, flanges, etc.)
- Specialty items (strainers, check valves, relief valves, etc.)
- Pipe support materials
- Bolting and gaskets
- Small bore piping and tubing
- Coverage of new booster pump station (5 x VS6-type pumps)
- Coverage of new 5x6 manifold
- Associated infrastructure at SW corner of TK-102

### 3.2 Excluded Scope
- Mechanical equipment (covered by PKG-03)
- Electrical materials (covered by PKG-05)
- Instrumentation materials (covered by PKG-07)
- Existing materials not modified
- Laurel Pump Station scope (explicitly excluded per SOW)

---

## 4. Technical Parameters

### 4.1 MTO Categories

| Category | Description | Data Source |
|----------|-------------|-------------|
| Pipe | Straight pipe lengths by size, class, schedule | Isometrics (DEL-02.13) |
| Fittings | Elbows, tees, reducers, caps, etc. | Isometrics (DEL-02.13) |
| Flanges | Weld neck, slip-on, blind, etc. | Isometrics (DEL-02.13) |
| Valves | Gate, ball, check, control, relief | Valve List (DEL-02.02) |
| Specialty Items | Strainers, filters, special fittings | Specialty Datasheets (DEL-02.20) |
| Bolting | Stud bolts, nuts, washers | PMC requirements |
| Gaskets | Spiral wound, ring joint, etc. | PMC requirements |
| Support Materials | Steel for supports, shoes, clamps | Support Drawings (DEL-02.16) |

### 4.2 Quantity Basis

| Phase | Quantity Basis | Accuracy Target |
|-------|----------------|-----------------|
| FEED | Preliminary (from 3D model/P&IDs) | +/- 20% (ASSUMPTION) |
| Detailed Design (IFD) | Design development | +/- 10% (ASSUMPTION) |
| Detailed Design (IFC) | Final (from approved isometrics) | +/- 5% (ASSUMPTION) |

### 4.3 Material Specifications (ASSUMPTION - per PMC)

| Material Category | Typical Specification |
|-------------------|----------------------|
| Carbon Steel Pipe | ASTM A106 Gr. B / API 5L |
| Carbon Steel Fittings | ASTM A234 WPB |
| Carbon Steel Flanges | ASTM A105 |
| Stainless Steel Pipe | ASTM A312 TP304/316 |
| Bolting | ASTM A193 B7 / A194 2H |
| Gaskets | ASME B16.20 Spiral Wound |

### 4.4 Estimated Material Quantities (ASSUMPTION)

| Category | Estimated Range | Notes |
|----------|-----------------|-------|
| Total Pipe Length | TBD (1,000-5,000 meters) | Based on scope |
| Valve Count | TBD (50-150 valves) | Based on P&IDs |
| Fitting Count | TBD (500-2,000 items) | Rule of thumb |
| Flange Pairs | TBD (100-400 pairs) | Based on connections |

---

## 5. Interface Requirements

| Interface | Related Deliverable | Description |
|-----------|---------------------|-------------|
| Isometrics | DEL-02.13 | Primary source for pipe/fittings |
| Valve List | DEL-02.02 | Valve quantities and specifications |
| LDT | DEL-02.18 | Line organization basis |
| PMC Index | DEL-02.25 | Material specifications |
| Specialty Items | DEL-02.20 | Specialty item specifications |
| Support Drawings | DEL-02.16 | Support material quantities |
| 3D Model | DEL-02.28 | Model-based quantities |
| Cost Estimate | PKG-00 | Cost basis input |
| Procurement | PKG-00 | Purchase order basis |

---

## 6. Deliverable Attributes

| Attribute | Requirement |
|-----------|-------------|
| File Format | Microsoft Excel (.xlsx) primary |
| PDF Export | Yes - for review/transmittal |
| Organization | By commodity, by line, or by area (TBD) |
| Summary Level | Detailed + Roll-up summaries |
| Revision Tracking | Version control per TM requirements |
| Pricing Columns | Optional - may include unit prices |

---

## 7. Quality Requirements

| Requirement | Description |
|-------------|-------------|
| Internal Check | Per Deliverable Review & Verification Plan (DEL-00.03) |
| Model Verification | Quantities verified against 3D model |
| Isometric Consistency | Quantities match isometric BOMs |
| Valve Reconciliation | Valve count matches Valve List |
| Specialty Item Verification | Specialty items match datasheets |

---

## 8. TBD Items

| Item | Description | Resolution Owner |
|------|-------------|------------------|
| TBD-01 | TM MTO template format | TM Procurement |
| TBD-02 | MTO organization structure | TM Piping Lead |
| TBD-03 | Accuracy requirements per phase | TM Project Controls |
| TBD-04 | Pricing requirements | TM Procurement |
| TBD-05 | Commodity codes / item numbering | TM |

---

## 9. Assumptions

| ID | Assumption | Impact if Invalid |
|----|------------|-------------------|
| ASSUMPTION-01 | MTO to be delivered in Excel format | Format conversion required |
| ASSUMPTION-02 | Quantities derived from 3D model and isometrics | Manual takeoff if no model |
| ASSUMPTION-03 | Standard PMC specifications apply | Additional spec work if non-standard |
| ASSUMPTION-04 | Accuracy targets as stated | Adjust contingency if different |

---

## 10. Source References

| Reference | Document | Section |
|-----------|----------|---------|
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.1.3.1 (p8) - FEED MTO |
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.9 (p19) - Isometrics/MTO |
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.12 (p20) - MTO development |
| Decomposition | Puget Sound Optimization Project Decomposition REVISED v2 | DEL-02.19, SOW-0127, SOW-0248, SOW-0251 |

---

*Document generated as initial draft. All TBD items and ASSUMPTIONS require verification during FEED/Detailed Design phases.*
