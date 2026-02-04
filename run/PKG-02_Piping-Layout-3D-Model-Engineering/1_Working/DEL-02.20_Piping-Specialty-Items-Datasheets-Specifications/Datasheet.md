# Datasheet: Piping Specialty Items Datasheets & Specifications

**Deliverable ID:** DEL-02.20
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Document Identification

| Field | Value |
|-------|-------|
| Document Number | TBD (per TM document numbering system) |
| Document Title | Piping Specialty Items Datasheets & Specifications |
| Revision | A (IFR) |
| Discipline | Piping |
| Project | Puget Sound Optimization Project (PSO) |
| Facility | Sumas Tank Farm (Sumas Terminal) |

---

## 2. Deliverable Summary

| Attribute | Value |
|-----------|-------|
| Deliverable Type | Data Sheet |
| Primary Output | Specialty item datasheets/specs, register |
| Responsible Party | Engineering Contractor |
| Phase Coverage | FEED + Detailed Design |
| Final Status Target | IFC (Issued for Construction) |

---

## 3. Scope Definition

### 3.1 Included Scope
- Datasheets for all piping specialty items within PSO scope
- Specifications for specialty items where not covered by TM standards
- Specialty item register/list
- Review and endorsement of manufacturer certified drawings
- Coverage of new booster pump station (5 x VS6-type pumps)
- Coverage of new 5x6 manifold system
- Associated infrastructure at SW corner of TK-102

### 3.2 Excluded Scope
- Standard valves (covered by DEL-02.02 Valve List)
- Standard pipe and fittings (covered by PMC)
- Mechanical equipment (covered by PKG-03)
- Instrumentation (covered by PKG-07)
- Laurel Pump Station scope (explicitly excluded per SOW)

---

## 4. Technical Parameters

### 4.1 Specialty Item Categories

| Category | Examples | Datasheet Required |
|----------|----------|-------------------|
| Strainers | Y-strainers, basket strainers, duplex strainers | Yes |
| Filters | Coalescing filters, cartridge filters | Yes |
| Expansion Joints | Bellows, slip joints | Yes |
| Flame Arrestors | In-line, end-of-line | Yes |
| Check Valves (special) | Wafer check, tilting disc, piston check | Yes |
| Relief Valves | Pressure relief, vacuum relief | Yes |
| Rupture Discs | Primary, secondary devices | Yes |
| Flow Elements | Orifice plates, flow nozzles | Yes |
| Sight Glasses | In-line, tubular | Yes |
| Spectacle Blinds | Figure-8 blinds | Yes |
| Special Fittings | Wyes, laterals, tees with unusual angles | Yes |
| Pig Launchers/Receivers | Pigging equipment | Yes (if applicable) |

### 4.2 Design Conditions (ASSUMPTION - per service)

| Parameter | Estimated Range | Source |
|-----------|-----------------|--------|
| Design Pressure | TBD (700-1400 kPag typical) | DBM (DEL-01.01) |
| Design Temperature | TBD (-29C to 50C typical) | DBM (DEL-01.01) |
| Operating Pressure | TBD | Process Data |
| Operating Temperature | TBD | Process Data |
| Fluid | Crude oil | P&ID / Process |
| Flow Rate | TBD (per equipment) | Process Data |

### 4.3 Applicable Codes and Standards

| Code/Standard | Description | Application |
|---------------|-------------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems | Primary code per SOW |
| ASME B31.4 | Pipeline Transportation Systems | Supplemental code |
| API 6D | Pipeline and Piping Valves | Valve requirements |
| API 594 | Check Valves | Check valve types |
| MSS SP-67 | Butterfly Valves | Butterfly valves |
| ASME Section VIII | Pressure Vessels | Strainers, filters |
| API 2000 | Venting | Tank vents, relief devices |

---

## 5. Interface Requirements

| Interface | Related Deliverable | Description |
|-----------|---------------------|-------------|
| P&IDs | DEL-01.03 | Specialty item identification |
| Valve List | DEL-02.02 | Valve specialty items |
| DBM | DEL-01.01 | Design conditions |
| PMC Index | DEL-02.25 | Material specifications |
| MTO | DEL-02.19 | Specialty item quantities |
| Isometrics | DEL-02.13 | Installation details |
| Procurement | PKG-00 | Requisition basis |
| Vendor | Manufacturer | Certified drawings |

---

## 6. Deliverable Attributes

### 6.1 Datasheet Attributes

| Attribute | Requirement |
|-----------|-------------|
| File Format | PDF (issued) + Native (Excel/Word) |
| Datasheet Template | TM standard or project template |
| Content | Technical requirements, materials, design data |
| Revisions | Tracked per TM document control |

### 6.2 Specialty Item Register

| Attribute | Requirement |
|-----------|-------------|
| File Format | Microsoft Excel (.xlsx) primary |
| Content | Item list, tag numbers, datasheets |
| Organization | By item type or tag number |

### 6.3 Estimated Quantities

| Item Type | Estimated Count | Notes |
|-----------|-----------------|-------|
| Strainers | TBD (5-15) | Based on pump suctions |
| Check Valves | TBD (10-30) | Based on P&IDs |
| Relief Devices | TBD (2-10) | Based on relief study |
| Other Specialty | TBD | To be determined |

---

## 7. Quality Requirements

| Requirement | Description |
|-------------|-------------|
| Internal Check | Per Deliverable Review & Verification Plan (DEL-00.03) |
| P&ID Consistency | All specialty items on P&IDs have datasheets |
| Design Verification | Design conditions match DBM |
| Code Compliance | Datasheets reference applicable codes |
| Vendor Review | Manufacturer drawings endorsed |

---

## 8. TBD Items

| Item | Description | Resolution Owner |
|------|-------------|------------------|
| TBD-01 | TM specialty item datasheet templates | TM Piping Lead |
| TBD-02 | Complete list of specialty items | Process / P&ID development |
| TBD-03 | Design pressure/temperature ranges | Process Engineering |
| TBD-04 | Specific specialty item requirements | TM |
| TBD-05 | Manufacturer approval list | TM Procurement |

---

## 9. Assumptions

| ID | Assumption | Impact if Invalid |
|----|------------|-------------------|
| ASSUMPTION-01 | Standard datasheet format acceptable | May need TM template |
| ASSUMPTION-02 | Specialty items identified from P&IDs | Additional items may emerge |
| ASSUMPTION-03 | Manufacturer drawings required for major items | Scope and schedule impact |
| ASSUMPTION-04 | Crude oil service as primary fluid | Different services need different specs |

---

## 10. Source References

| Reference | Document | Section |
|-----------|----------|---------|
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.1.3.1 (p7) - FEED datasheets |
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.17 (p20) - Specialty items |
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.25 (p21) - Detailed deliverables |
| Decomposition | Puget Sound Optimization Project Decomposition REVISED v2 | DEL-02.20, SOW-0119, SOW-0256, SOW-0260 |

---

*Document generated as initial draft. All TBD items and ASSUMPTIONS require verification during FEED/Detailed Design phases.*
