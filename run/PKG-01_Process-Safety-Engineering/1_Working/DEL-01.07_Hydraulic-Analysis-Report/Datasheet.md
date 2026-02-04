# Datasheet: DEL-01.07 Hydraulic Analysis Report

**Document ID:** DEL-01.07-DS
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.07 |
| Deliverable Name | Hydraulic Analysis Report |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Report |
| Responsible Party | Engineering Contractor |

---

## 2. Attributes

### 2.1 Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Project Phase | FEED + Detailed Design | Per decomposition; refined through IFC |
| Analysis Type | Steady-state hydraulic analysis | Pipe flow/pressure drop calculations |
| Coordination Required | TM Hydraulic Analyst / Puget System Model | Per SOW-0130, SOW-0220 |
| Primary Systems | Booster pump station, 5x6 manifold, associated piping | Per PSO scope at Sumas Tank Farm |
| Software Tools | **TBD** - Industry-standard hydraulic modeling software | To be selected during project execution |

### 2.2 Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | Hydraulic analysis report(s), model inputs/outputs |
| Native Format | Modeling software + Word/Excel/PDF |
| Deliverable Format | PDF + Native editable files + Model files |
| Revision Cycle | IFR -> IFD -> IFC |

### 2.3 Analysis Scope

| System/Component | Analysis Type | Notes |
|------------------|---------------|-------|
| Booster Pump Performance | Pump curves, NPSH, operating points | 5 VS6-type pumps; 70-110% BEP operating range |
| Manifold Hydraulics | Pressure drop, flow distribution | 5x6 manifold per SOW (Note: DBM references 6x5 - TBD confirmation) |
| Suction Piping | Pressure drop, NPSH available | From TK-101/TK-102 tanks |
| Discharge Piping | Pressure drop, velocity | To Puget Sound Pipeline |
| Blending System | Flow ratio control, mixing | 20%/80% Heavy/Light baseline; 10%-100% NEAT extended range |

---

## 3. Conditions

### 3.1 Design Flow Conditions

| Parameter | Sustainable | Design (Peak) | Source |
|-----------|-------------|---------------|--------|
| Flow Rate | 275,000 bpd (1,822 m3/h) | 315,000 bpd (2,100 m3/h) | SOW-0002 |
| Number of Operating Pumps | **TBD** | **TBD** | Per hydraulic optimization |
| Pump Configuration | 2 large + 2 small + 1 medium | Same | SOW-0004 |

### 3.2 Fluid Properties

| Parameter | Heavy Crude | Light Crude | Blended | Notes |
|-----------|-------------|-------------|---------|-------|
| Density | **TBD** kg/m3 | **TBD** kg/m3 | **TBD** kg/m3 | At operating conditions |
| Viscosity | **TBD** cSt | **TBD** cSt | **TBD** cSt | At operating conditions |
| Blend Ratio | 20% (baseline) | 80% (baseline) | 100% | Baseline per SOW-0005; Extended range 10%-100% NEAT per DBM |
| Vapor Pressure | **TBD** kPa | **TBD** kPa | **TBD** kPa | For NPSH calculations |

### 3.3 System Pressure Conditions

| Location | Min Pressure | Normal Pressure | Max Pressure | Notes |
|----------|--------------|-----------------|--------------|-------|
| Tank Suction | **TBD** kPag | **TBD** kPag | **TBD** kPag | Static head from tanks |
| Pump Suction | **TBD** kPag | **TBD** kPag | **TBD** kPag | NPSHa verification (margin >= 1.0m above NPSHr) |
| Pump Discharge | **TBD** kPag | **TBD** kPag | **TBD** kPag | Operating envelope |
| Delivery Point | **TBD** kPag | **TBD** kPag | **TBD** kPag | Battery limit pressure |

### 3.4 Operating Cases

| Case ID | Description | Flow Rate | Pump Config | Fluid | Notes |
|---------|-------------|-----------|-------------|-------|-------|
| Case 1 | Normal Operation - Sustainable | 1,822 m3/h | **TBD** | Blended 20/80 | Baseline case |
| Case 2 | Peak Operation | 2,100 m3/h | **TBD** | Blended 20/80 | Design case |
| Case 3 | Minimum Turndown | **TBD** | **TBD** | Blended 20/80 | Single pump operation |
| Case 4 | Tank-to-Tank Transfer | **TBD** | **TBD** | **TBD** | Per DBM requirement |
| Case 5 | Heavy Component NEAT | **TBD** | **TBD** | Heavy 100% | Extended range per DBM |
| Case 6 | Light Component NEAT | **TBD** | **TBD** | Light 100% | Extended range per DBM |

---

## 4. Construction

### 4.1 Report Content Requirements

The Hydraulic Analysis Report shall include:
- Executive summary with key findings
- System description and scope boundaries
- Methodology and assumptions
- Fluid property basis
- Piping and equipment data
- Pump performance curves and operating points
- Hydraulic calculations and pressure profiles
- NPSH verification (NPSHa >= NPSHr + 1.0m minimum margin)
- Sensitivity analyses
- Optimization recommendations
- Conclusions and recommendations
- Appendices (model outputs, data sheets)

### 4.2 Analysis Requirements

| Requirement | Scope | Notes |
|-------------|-------|-------|
| Pressure Drop Calculation | All process piping | Per Darcy-Weisbach or equivalent |
| Pump Selection Verification | All 5 booster pumps | Operating points 70-110% BEP on pump curves |
| NPSH Analysis | All pump suctions | NPSHa >= NPSHr + 1.0m minimum margin |
| Velocity Check | All lines | Per DEL-01.05 line sizing criteria |
| Control Valve Sizing | Flow control valves | Cv requirements |
| System Curve Development | Complete system | For pump selection |

### 4.3 Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Design Basis (DBM) | DEL-01.01 | Required |
| Process Flow Diagrams | DEL-01.02 | Required |
| P&IDs | DEL-01.03 | Concurrent |
| Equipment Sizing | DEL-01.04 | Concurrent |
| Line Sizing | DEL-01.05 | Concurrent |
| Existing TM Puget System Model | TM | **TBD** - Coordination required |
| Appendix C - Draft Hydraulic Report | Reference input | Preliminary basis |

---

## 5. References

### 5.1 Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0130: Refine hydraulic model with TM hydraulic analyst / Puget system model |
| SOW Reference | SOW-0220: Update TM hydraulic model and hydraulic analysis to IFC status |
| SOW Reference | SOW-0232: Provide IFC process deliverables including hydraulic reports |
| Reference Input | Appendix C - Draft PSO Hydraulic Report REV 0 (2025-07-16) |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### 5.2 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | DBM provides design basis including blend ratios and operating envelope |
| DEL-01.02 | PFDs show system configuration |
| DEL-01.03 | P&IDs provide detailed equipment/piping data |
| DEL-01.04 | Equipment sizing provides pump/vessel data |
| DEL-01.05 | Line sizing provides pipe dimensions and velocity criteria |
| DEL-01.06 | Relief calculations use hydraulic pressures |
| DEL-01.08 | Transient analysis builds on steady-state model |
| DEL-01.13 | Operating envelopes derived from hydraulic analysis |

### 5.3 Applicable Standards

| Standard | Description |
|----------|-------------|
| API 610 | Centrifugal Pumps for Petroleum, Petrochemical and Natural Gas Industries |
| Hydraulic Institute Standards | Pump application guidelines including NPSH margins and operating range |
| CSA Z662 | Oil and Gas Pipeline Systems |
| ASME B31.4 | Pipeline Transportation Systems for Liquids |
| Crane TP-410 | Flow of Fluids Through Valves, Fittings, and Pipe (reference) |
| TM Standards | Trans Mountain project-specific standards (**TBD**) |

---

*End of Datasheet*
