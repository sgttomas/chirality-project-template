# Datasheet: DEL-01.05 Line Sizing Calculations

**Document ID:** DEL-01.05-DS
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.05 |
| Deliverable Name | Line Sizing Calculations |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Calculation |
| Responsible Party | Engineering Contractor |

---

## Attributes

### Technical Attributes

| Parameter | Value | Units | Source |
|-----------|-------|-------|--------|
| Sustainable Flow Rate | 275,000 | bpd | SOW §2.2.1 |
| Sustainable Flow Rate | 1,822 | m³/h | Converted |
| Design (Peak) Flow Rate | 315,000 | bpd | SOW §2.2.1 |
| Design (Peak) Flow Rate | 2,100 | m³/h | Converted |
| Manifold Configuration | 5x6 (5 inlet, 6 outlet) | - | SOW §2.3.1.1 |
| Pump Configuration | 5 VS6-type booster pumps | - | SOW §2.3.1.1 |

### Line Categories

| Category | Description | Sizing Basis | Source |
|----------|-------------|--------------|--------|
| Tank Suction Headers | From tanks to manifold suction | Peak flow, velocity limits | SOW §2.3.1.1 |
| Manifold Headers (5x6) | 5 inlet headers and 6 outlet headers | Peak flow, velocity limits | SOW §2.3.1.1 |
| Pump Suction Lines | Manifold to pump suction | Individual pump flow, NPSHa | SOW §2.3.1.1 |
| Pump Discharge Lines | Pump discharge to headers | Individual pump flow, velocity limits | SOW §2.3.1.1 |
| Discharge Headers | Combined to pipeline | Peak flow, velocity limits | SOW §2.3.1.1 |
| Blending Lines | Heavy/Light component lines | Blending ratio flows | SOW §2.3.1.4 |
| Auxiliary Lines | Sump, reinjection, drains | Service-specific | SOW §3.2.3.10 |

### Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | Calculation report(s) |
| Native Format | Excel/MathCAD/Word (editable) |
| Deliverable Format | PDF + Native editable files per SOW-0231 |
| Revision Cycle | IFR → IFD → IFC |
| Phase Coverage | FEED + Detailed Design |

---

## Conditions

### Design Conditions

| Parameter | Value | Units | Source |
|-----------|-------|-------|--------|
| Design Flow Rate (Peak) | 315,000 | bpd | SOW §2.2.1 - sizing basis |
| Design Flow Rate (Peak) | 2,100 | m³/h | Converted |
| Sustainable Flow Rate | 275,000 | bpd | SOW §2.2.1 |
| Design Pressure | **TBD** | kPag | Per DEL-01.01 DBM |
| Design Temperature | **TBD** | °C | Per DEL-01.01 DBM |
| Fluid Density | **TBD** | kg/m³ | Per DEL-01.01 DBM |
| Fluid Viscosity | **TBD** | cSt | Per DEL-01.01 DBM |

### Sizing Criteria

| Criterion | Suction Lines | Discharge Lines | Headers | Source |
|-----------|---------------|-----------------|---------|--------|
| Velocity Limit | **TBD** | **TBD** | **TBD** | **ASSUMPTION:** 1.0-2.0 m/s suction, 3.0-5.0 m/s discharge |
| Pressure Drop | **TBD** | **TBD** | **TBD** | Per hydraulic optimization (DEL-01.07) |
| Erosion Limit | **TBD** | **TBD** | **TBD** | Per code requirements |

---

## Construction

### Calculation Content Requirements

Line sizing calculations shall include:
- Design basis summary (from DEL-01.01)
- Hydraulic data inputs (from DEL-01.07)
- Velocity calculations for all line categories
- Pressure drop calculations
- Line size recommendations
- Piping class designation
- Assumptions and TBDs log
- References to applicable standards
- Coordination with DEL-01.04 (Equipment Sizing)
- Support for DEL-02.01 (Line List)

### Calculation Methodology

| Calculation | Methodology | Key Parameters |
|-------------|-------------|----------------|
| Velocity | V = Q / A | Flow rate, line diameter |
| Pressure Drop | Darcy-Weisbach or equivalent | Friction factor, L/D, fittings |
| Line Sizing | Economic velocity / allowable dP | Flow, velocity limits, dP budget |
| Pipe Class | Per service, P/T, material | Design conditions, material spec |

### Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Design Basis (DBM) | DEL-01.01 | Required |
| Hydraulic Analysis | DEL-01.07 | Required |
| Equipment Sizing | DEL-01.04 | Concurrent |
| PFDs | DEL-01.02 | Required |
| Fluid Properties | DEL-01.01 / TM | **TBD** |
| Piping Material Classes | TMP Standards (Attachment A08) | **TBD** |

---

## References

### Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0114: Produce FEED line sizing calculations |
| SOW Reference | SOW-0130: Refine hydraulic model, optimize piping/valve sizes |
| SOW Reference | SOW-0231: Submit editable native files for line sizing calculations |
| Hydraulic Report | Appendix C-Draft PSO - Hydraulic Report - REV 0 - 25.07.16.pdf |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | DBM provides design basis and fluid properties |
| DEL-01.02 | PFDs provide process overview |
| DEL-01.03 | P&IDs show line configuration |
| DEL-01.04 | Equipment sizing (interdependent) |
| DEL-01.07 | Hydraulic analysis provides pressure/flow data |
| DEL-02.01 | Line List derived from sizing |
| DEL-00.01 | MDR registration required |

### Applicable Standards

| Standard | Description |
|----------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems |
| ASME B31.4 | Pipeline Transportation Systems for Liquids |
| API RP 14E | Erosional velocity limits (reference) |
| TMP Standards | **TBD** - Per Attachment A08 |

---

*End of Datasheet*
