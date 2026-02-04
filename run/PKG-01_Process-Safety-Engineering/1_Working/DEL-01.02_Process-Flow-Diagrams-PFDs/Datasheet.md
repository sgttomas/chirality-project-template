# Datasheet: DEL-01.02 Process Flow Diagrams (PFDs)

**Document ID:** DEL-01.02-DS
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.02 |
| Deliverable Name | Process Flow Diagrams (PFDs) |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Drawing |
| Responsible Party | Engineering Contractor |

---

## Attributes

### Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Drawing Size | **TBD** | **ASSUMPTION:** D-size (22"x34") typical |
| Drawing Format | CAD (AutoCAD/MicroStation) | Per TM requirements |
| Scale | Not to scale (schematic) | Standard for PFDs |
| Numbering Convention | **TBD** | Per TM drawing numbering system |

### Drawing Set Composition

| Component | Estimated Count | Notes |
|-----------|-----------------|-------|
| Overall System PFD | 1 | System overview - booster pumps, manifold, blending |
| Booster Pump System PFD | **TBD** | 5 VS6-type pumps (2 Large + 2 Small + 1 Medium) |
| Manifold System PFD | **TBD** | 5x6 manifold header system |
| Legend/Symbol Sheet | 1 | Per TM standards |

### Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | PFD drawing set |
| Native Format | CAD (dwg/dgn) |
| Deliverable Format | PDF + Native CAD files per SOW §3.2.3.18 |
| Revision Cycle | IFR → IFD → IFC |
| Phase Coverage | FEED through Detailed Design |

---

## Conditions

### Process Conditions

| Parameter | Value | Units | Source |
|-----------|-------|-------|--------|
| Sustainable Flow Rate | 275,000 | bpd | SOW §2.2.1 |
| Sustainable Flow Rate | 1,822 | m³/h | Converted |
| Design (Peak) Flow Rate | 315,000 | bpd | SOW §2.2.1 |
| Design (Peak) Flow Rate | 2,100 | m³/h | Converted |
| Blending Ratio (SOW) | 20% Heavy to 80% Light | - | SOW §2.3.1.4 |
| Blending Range (DBM) | 10%-100% NEAT | - | DBM §2.2.2.2 |
| Design Pressure | **TBD** | kPag | Per DEL-01.01 DBM |
| Design Temperature | **TBD** | °C | Per DEL-01.01 DBM |

### Heat and Material Balance

| Parameter | Unit | Value | Notes |
|-----------|------|-------|-------|
| Total System Flow | m³/h | 2,100 | Design (peak) case |
| Fluid Density | kg/m³ | **TBD** | At operating conditions |
| Fluid Viscosity | cSt | **TBD** | At operating conditions |
| Heat Duty | kW | **TBD** | If applicable |

---

## Construction

### PFD Content Requirements

Each PFD shall include:
- Process flow lines with flow direction arrows
- Major equipment items with tag numbers (5 VS6 pumps: 2 Large + 2 Small + 1 Medium, manifold, tanks)
- Stream numbers and stream data table
- Heat and material balance table (or reference)
- Operating conditions (pressure, temperature, flow) per DEL-01.01 DBM
- Control philosophy (basic loops) - blending ratio control
- Battery limit indications to existing Sumas Terminal
- Reference to detailed P&IDs (DEL-01.03)
- VFD and flow meter indications per pump

### Equipment Representation

| Equipment Type | Quantity | Symbol Standard | Notes |
|----------------|----------|-----------------|-------|
| Booster Pumps (VS6) | 5 | TM Standard / ISA | 2 Large + 2 Small + 1 Medium per SOW §2.3.1.2 |
| VFDs | 5 | TM Standard | One per pump per SOW §2.3.1.4 |
| Flow Meters | 5 | TM Standard / ISA | Discharge, per SOW §2.3.1.4 |
| Manifold | 5x6 | TM Standard | Per SOW §2.3.1.1 |
| Control Valves | **TBD** | TM Standard / ISA | Major blending/isolation |
| Tanks | Reference | TM Standard | TK-102 area reference |

### Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Design Basis (DBM) | DEL-01.01 | Required |
| TM Symbol Library | TM Standards | **TBD** |
| Hydraulic Analysis | DEL-01.07 | Concurrent |
| Existing PFDs | TM Archives | **TBD** |
| Input PFD | Appendix B-PFD-xxxx-ST00-GSxxxx_0_IFR_2025-05-16.pdf | Available |

---

## References

### Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0111: Produce FEED PFDs (GS) |
| SOW Reference | SOW-0230: Finalize PFDs to IFC incorporating HAZOP/model review/change notice/vendor data updates |
| Input PFD | Appendix B-PFD-xxxx-ST00-GSxxxx_0_IFR_2025-05-16.pdf |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | DBM provides design basis |
| DEL-01.03 | P&IDs developed from PFDs |
| DEL-01.07 | Hydraulic Analysis supports flow data |
| DEL-01.15 | PFDs updated per HAZOP findings |
| DEL-00.01 | MDR registration required |

### Applicable Standards

| Standard | Description |
|----------|-------------|
| ISA 5.1 | Instrumentation Symbols and Identification |
| TM Drawing Standards | **TBD** - Project-specific |
| API RP 14C | Analysis, Design, Installation of Process Safety Systems (reference) |

---

*End of Datasheet*
