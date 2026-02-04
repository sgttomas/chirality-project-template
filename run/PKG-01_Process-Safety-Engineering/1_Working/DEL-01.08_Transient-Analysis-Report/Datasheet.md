# Datasheet: DEL-01.08 Transient Analysis Report

**Document ID:** DEL-01.08-DS
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.08 |
| Deliverable Name | Transient Analysis Report |
| Parent Package | PKG-01 Process Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Report |
| Responsible Party | Engineering Contractor |

---

## 2. Attributes

### 2.1 Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Project Phase | FEED + Detailed Design | Per decomposition |
| Analysis Type | Transient hydraulic analysis (surge/waterhammer) | Dynamic simulation |
| Primary Phenomena | Pressure surge, waterhammer, column separation | As applicable to scope |
| Primary Systems | Booster pump station, manifold, piping systems | Per PSO scope at Sumas Tank Farm |
| Software Tools | Industry-standard transient analysis software | AFT Impulse, PIPENET Transient, or Synergi Pipeline Simulator |

### 2.2 Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | Transient analysis report(s) |
| Native Format | Modeling software + Word/Excel/PDF |
| Deliverable Format | PDF + Native editable files + Model files |
| Revision Cycle | IFR -> IFD -> IFC |

### 2.3 Analysis Scope

| System/Component | Transient Event | Notes |
|------------------|-----------------|-------|
| Booster Pumps | Pump trip (single/multiple) | Most critical transient |
| Booster Pumps | Pump startup | Sequential/simultaneous |
| Control Valves | Rapid closure/opening | Control system response |
| Check Valves | Slam/reverse flow | Pump discharge check valves |
| Emergency Shutdown | ESD valve closure | If applicable |
| VFD Response | Variable speed transitions | Per pump configuration |

---

## 3. Conditions

### 3.1 System Parameters

| Parameter | Value | Source |
|-----------|-------|--------|
| Pipeline Length (affected) | **TBD** m | System boundaries |
| Pipe Diameters | **TBD** mm | Per DEL-01.05 |
| Pipe Wall Thickness | **TBD** mm | Per DEL-01.05 |
| Pipe Material | Carbon steel | **ASSUMPTION:** Per TM standards |
| Pressure Wave Speed | **TBD** m/s | Calculated from pipe/fluid properties |

### 3.2 Operating Conditions (Base Case)

| Parameter | Value | Notes |
|-----------|-------|-------|
| Normal Flow Rate | 1,822 m3/h | Sustainable rate |
| Maximum Flow Rate | 2,100 m3/h | Peak/design rate |
| Operating Pressure | **TBD** kPag | Per DEL-01.07 hydraulic analysis |
| Fluid Density | **TBD** kg/m3 | At operating temperature |
| Fluid Bulk Modulus | **TBD** GPa | For wave speed calculation |

### 3.3 Transient Event Parameters

| Event | Closure/Trip Time | Frequency | Notes |
|-------|-------------------|-----------|-------|
| Pump Trip (power failure) | Instantaneous | Per design basis | Worst case |
| Pump Trip (controlled) | **TBD** seconds | Per VFD settings | VFD controlled rundown |
| Control Valve Closure | **TBD** seconds | Normal operation | Per valve actuator |
| Emergency Valve Closure | **TBD** seconds | Emergency | If ESD valves present |
| Check Valve Closure | **TBD** seconds | Each pump trip | Per manufacturer data |

### 3.4 Acceptance Criteria

| Parameter | Limit | Notes |
|-----------|-------|-------|
| Maximum Surge Pressure | **TBD** kPag | Below design pressure with margin per ASME B31.4 |
| Minimum Surge Pressure | **TBD** kPag | Above vapor pressure (no column separation) |
| Maximum Pressure Rise Rate | **TBD** kPa/s | If specified by TM or equipment vendor |
| Check Valve Slam Velocity | **TBD** m/s | Per manufacturer limits |

---

## 4. Construction

### 4.1 Report Content Requirements

The Transient Analysis Report shall include:
- Executive summary with key findings
- System description and model boundaries
- Methodology and software description
- Input data and assumptions
- Transient event scenarios analyzed
- Analysis results (pressure/flow vs. time plots)
- Maximum/minimum pressure envelopes
- Mitigation measures (if required)
- Conclusions and recommendations
- Appendices (model outputs, time history data)

### 4.2 Transient Scenarios to Analyze

| Scenario ID | Description | Priority | Notes |
|-------------|-------------|----------|-------|
| TS-01 | Single pump trip at max flow | High | Base case |
| TS-02 | All pumps trip (power failure) | High | Worst case |
| TS-03 | Pump startup (single) | Medium | Normal operation |
| TS-04 | Sequential pump startup | Medium | Multiple pumps |
| TS-05 | Control valve failure closed | High | If applicable |
| TS-06 | Check valve slam | High | Reverse flow scenario |
| TS-07 | VFD speed change transient | Medium | Normal operation |
| TS-08 | Emergency shutdown valve closure | High | If ESD system present |

### 4.3 Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Design Basis Memorandum | DEL-01.01 | Required |
| Process Flow Diagrams | DEL-01.02 | Required |
| P&IDs | DEL-01.03 | Required |
| Equipment Sizing | DEL-01.04 | Required (pump data) |
| Line Sizing | DEL-01.05 | Required (pipe data) |
| Hydraulic Analysis | DEL-01.07 | Required (steady-state basis) |
| Pump Vendor Data | Vendor | Required for IFC (pump inertia, curves) |
| Valve Vendor Data | Vendor | Required for IFC (closure characteristics) |

---

## 5. References

### 5.1 Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0232: Provide IFC process deliverables including transient reports |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |
| Reference Input | Appendix C - Draft PSO Hydraulic Report REV 0 (for system data) |

### 5.2 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | Design Basis Memorandum provides design basis and operating conditions |
| DEL-01.02 | Process Flow Diagrams show system configuration |
| DEL-01.03 | P&IDs provide equipment/valve details |
| DEL-01.04 | Equipment sizing provides pump characteristics |
| DEL-01.05 | Line sizing provides pipe dimensions |
| DEL-01.06 | Relief calculations may use surge pressures from transient analysis |
| DEL-01.07 | Hydraulic analysis provides steady-state basis |
| DEL-01.13 | Operating envelopes include transient limits |
| DEL-01.15 | HAZOP identifies transient scenarios |
| PKG-07 | Controls & instrumentation provides valve timing data |

### 5.3 Applicable Standards

| Standard | Description |
|----------|-------------|
| ASME B31.4 | Pipeline Transportation Systems for Liquids |
| API 1160 | Managing System Integrity for Hazardous Liquid Pipelines |
| CSA Z662 | Oil and Gas Pipeline Systems |
| AWWA M11 | Steel Pipe - A Guide for Design and Installation (reference for surge) |
| CER Regulations | Canadian Energy Regulator pipeline safety requirements |
| Title 49 CFR Part 195 | U.S. Federal regulations for hazardous liquid pipelines |

---

*End of Datasheet*
