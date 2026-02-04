# Datasheet: Line Designation Table (LDT)

**Deliverable ID:** DEL-02.18
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Document Identification

| Field | Value |
|-------|-------|
| Document Number | TBD (per TM document numbering system) |
| Document Title | Line Designation Table (LDT) |
| Revision | A (IFR) |
| Discipline | Piping |
| Project | Puget Sound Optimization Project (PSO) |
| Facility | Sumas Tank Farm (Sumas Terminal) |

---

## 2. Deliverable Summary

| Attribute | Value |
|-----------|-------|
| Deliverable Type | Table |
| Primary Output | LDT (Excel) |
| Responsible Party | Engineering Contractor |
| Phase Coverage | FEED + Detailed Design |
| Final Status Target | IFC (Issued for Construction) |

---

## 3. Scope Definition

### 3.1 Included Scope
- Process piping line designation table for all new lines within PSO scope
- Coverage of new booster pump station piping (5 x VS6-type pumps)
- Coverage of new 5x6 manifold piping
- Coverage of associated infrastructure at SW corner of TK-102
- All required attributes per SOW Section 3.2.4.11
- Tie-in lines to existing systems

### 3.2 Excluded Scope
- Existing lines not modified by PSO scope
- Laurel Pump Station scope (explicitly excluded per SOW)
- Utility lines outside piping discipline ownership

---

## 4. Technical Parameters

### 4.1 LDT Column Structure

| Column | Description | Data Source |
|--------|-------------|-------------|
| Line Number | Unique line identifier per TM convention | Engineering |
| P&ID Reference | Associated P&ID sheet number | DEL-01.03 |
| Line Size | Nominal pipe size (NPS) | Process / Engineering |
| Piping Class | Material class per PMC Index | DEL-02.25 |
| From | Origin equipment/node | P&ID / Engineering |
| To | Destination equipment/node | P&ID / Engineering |
| Design Pressure | Design pressure (kPag or psig) | DEL-01.01 / Process |
| Design Temperature | Design temperature (C or F) | DEL-01.01 / Process |
| Operating Pressure | Normal operating pressure | DEL-01.01 / Process |
| Operating Temperature | Normal operating temperature | DEL-01.01 / Process |
| Service/Fluid | Process fluid description | P&ID / Process |
| Insulation | Insulation code/thickness | Insulation Schedule |
| Heat Tracing | Heat tracing requirements | Insulation Schedule |
| NDE Requirements | Radiography/UT/MT/PT code | PMC / Spec |
| PWHT Requirements | Post-weld heat treatment | PMC / Stress |
| Hydro Test Pressure | Hydrotest pressure | Calculations |
| Leak Test | Leak test requirements | Spec |
| Painting/Coating | External coating specification | Coating Spec |
| Line Status | New/Existing/Modified/Demolished | Engineering |
| Remarks | Additional notes | Engineering |

### 4.2 Line Numbering Convention (ASSUMPTION)

| Element | Format | Example |
|---------|--------|---------|
| Area Prefix | XX | PS (Pump Station) |
| Fluid Code | XXX | CRU (Crude) |
| Sequence | XXXX | 0001 |
| Size | XX | 16 (NPS 16) |
| Spec Class | XXX | A1A |

ASSUMPTION: Line numbering convention follows TM standard format - to be verified.

### 4.3 Design Conditions (ASSUMPTION - from DBM/Process)

| Parameter | Estimated Range | Source |
|-----------|-----------------|--------|
| Design Pressure | TBD (700-1400 kPag typical) | DBM |
| Design Temperature | TBD (-29C to 50C typical) | DBM |
| Operating Pressure | TBD | Process Data |
| Operating Temperature | TBD | Process Data |
| Pipe Sizes | 2" to 24" NPS (estimated) | Preliminary Line List |

---

## 5. Interface Requirements

| Interface | Related Deliverable | Description |
|-----------|---------------------|-------------|
| P&IDs | DEL-01.03 | Line tags and routing |
| DBM | DEL-01.01 | Design conditions |
| Line List | DEL-02.01 | Initial line identification |
| PMC Index | DEL-02.25 | Material class designations |
| Stress Analysis | DEL-02.14 | PWHT and NDE requirements |
| Isometrics | DEL-02.13 | Line number callouts |
| MTO | DEL-02.19 | Line-based material quantities |
| Hydrotest | DEL-02.21 | Test pressure data |

---

## 6. Deliverable Attributes

| Attribute | Requirement |
|-----------|-------------|
| File Format | Microsoft Excel (.xlsx) primary |
| PDF Export | Yes - for review/transmittal |
| Column Count | TBD (20-30 columns typical) |
| Row Count | TBD (50-200 lines estimated) |
| Filter/Sort | Enabled for all columns |
| Revision Tracking | Version control per TM requirements |
| Data Validation | Dropdown lists for coded fields |

---

## 7. Quality Requirements

| Requirement | Description |
|-------------|-------------|
| Internal Check | Per Deliverable Review & Verification Plan (DEL-00.03) |
| P&ID Consistency | All LDT lines traceable to P&IDs |
| PMC Validation | All pipe classes valid per PMC Index |
| Completeness | All lines within scope captured |
| Data Integrity | No blank mandatory fields |

---

## 8. TBD Items

| Item | Description | Resolution Owner |
|------|-------------|------------------|
| TBD-01 | TM LDT template format (if existing) | TM Piping Lead |
| TBD-02 | Line numbering convention | TM |
| TBD-03 | Full column requirements | TM Piping Lead |
| TBD-04 | Design pressure/temperature ranges | Process Engineering |
| TBD-05 | NDE/PWHT requirements per line class | TM Specs |

---

## 9. Assumptions

| ID | Assumption | Impact if Invalid |
|----|------------|-------------------|
| ASSUMPTION-01 | LDT to be delivered in Excel format | Format conversion may be required |
| ASSUMPTION-02 | Column structure follows industry standard | May need additional/different columns |
| ASSUMPTION-03 | 50-200 lines estimated for PSO scope | Effort adjustment if significantly more |

---

## 10. Source References

| Reference | Document | Section |
|-----------|----------|---------|
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.11 (p19) |
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.23-24 (p21) - Native file requirements |
| Decomposition | Puget Sound Optimization Project Decomposition REVISED v2 | DEL-02.18, SOW-0250, SOW-0259 |

---

*Document generated as initial draft. All TBD items and ASSUMPTIONS require verification during FEED/Detailed Design phases.*
