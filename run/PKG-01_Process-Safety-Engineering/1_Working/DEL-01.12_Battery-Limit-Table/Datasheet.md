# Datasheet: DEL-01.12 Battery Limit Table

**Document ID:** DEL-01.12-DS
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.12 |
| Deliverable Name | Battery Limit Table |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Table |
| Responsible Party | Engineering Contractor |

---

## 2. Attributes

### 2.1 Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Project Phase | Detailed Design | Per SOW-0232 (IFC deliverables set) |
| Facility Location | Sumas Tank Farm | Per PSO project scope |
| Interface Type | Process/mechanical battery limits | Tie-in points to existing facilities |
| Format | Tabular summary | Per SOW-0232 requirement |

### 2.2 Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | Battery Limit Table |
| Native Format | Excel (.xlsx) |
| Deliverable Format | PDF + Excel native |
| Revision Cycle | IFR -> IFD -> IFC |

---

## 3. Conditions

### 3.1 Battery Limit Categories

| Interface Type | Description | Notes |
|----------------|-------------|-------|
| Process Piping | Tie-in points to existing piping | Suction/discharge connections |
| Electrical | Power supply connection points | Coordinate with PKG-06 Electrical |
| Instrumentation | Signal/control interface points | Coordinate with PKG-07 Instrumentation & Controls |
| Civil/Structural | Foundation/support interfaces | Coordinate with PKG-04 Civil/Structural |
| Utilities | Utility supply connection points | Instrument air, cooling water, fire water |

### 3.2 Process Interfaces (per SOW and DBM)

| Interface | Description | Source |
|-----------|-------------|--------|
| Tank TK-102 Suction | Existing tank farm piping (Heavy Crude) | SOW Section 2.3.1.1; DBM Section 2.2 |
| Tank TK-101 Suction | Existing tank farm piping (Light Crude) | SOW Section 2.3.1.1; DBM Section 2.2 |
| Puget Sound Pipeline | Discharge to delivery pipeline | SOW Section 2.1; DBM Section 2.2 |
| Existing Manifold | Tie-in to existing 5x6 header system | DBM Section 2.2.2 |

### 3.3 Design Conditions at Battery Limits

| Parameter | Value | Notes |
|-----------|-------|-------|
| Design Pressure (suction) | Per hydraulic analysis | From DEL-01.07 Hydraulic Analysis |
| Design Pressure (discharge) | Per hydraulic analysis | From DEL-01.07 Hydraulic Analysis |
| Design Temperature (max) | Per DBM | From DEL-01.01 Design Basis Memorandum |
| Design Temperature (min) | Per DBM | From DEL-01.01 Design Basis Memorandum |
| Flow Rate (sustainable) | 275,000 bpd (1,822 m³/h) | SOW Section 2.2.1 |
| Flow Rate (peak) | 315,000 bpd (2,100 m³/h) | SOW Section 2.2.1 |

---

## 4. Construction

### 4.1 Table Structure (Standard Format)

| Column | Description |
|--------|-------------|
| Battery Limit ID | Unique identifier for each interface point |
| P&ID Reference | Drawing reference (from DEL-01.03) |
| Line Number | Associated line designation (from DEL-02.01) |
| Service/Description | Fluid service and description |
| Direction | Into scope (IN) or out of scope (OUT) |
| Size | Nominal pipe size (NPS) |
| Rating/Class | Pressure class/rating (ASME B16.5) |
| Design Pressure | Maximum design pressure (kPa gauge) |
| Design Temperature | Design temperature range (°C) |
| Normal Flow | Typical operating flow rate (m³/h) |
| Normal Pressure | Typical operating pressure (kPa gauge) |
| Normal Temperature | Typical operating temperature (°C) |
| Fluid Composition | Fluid type/composition |
| Insulation | Insulation requirements (if any) |
| Heat Tracing | Heat tracing requirements (if any) |
| Remarks | Notes, references, special requirements |

### 4.2 Content Requirements

The Battery Limit Table shall include:
- All process piping interfaces between PSO scope and existing facilities
- Design conditions at each interface point (per DEL-01.01 and DEL-01.07)
- Normal operating conditions at each interface point
- Fluid properties at each interface point (per DEL-01.01)
- Cross-reference to P&IDs (DEL-01.03) and tie-in list (DEL-02.03)
- Coordination with line list (DEL-02.01) for line designations

### 4.3 Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Process Design Basis Memorandum | DEL-01.01 | Required before start |
| P&IDs | DEL-01.03 | Required for interface identification |
| Hydraulic Analysis | DEL-01.07 | Required for pressure/flow conditions |
| Line List | DEL-02.01 | Required for line designations |
| Tie-In List | DEL-02.03 | Required for interface coordination |
| Existing Facility P&IDs | TM Document Control | Required for existing conditions |

---

## 5. References

### 5.1 Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0232: "Provide IFC process deliverables set including... battery limit table..." |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### 5.2 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | Design Basis Memorandum provides design parameters |
| DEL-01.03 | P&IDs show interface locations and line routing |
| DEL-01.07 | Hydraulic Analysis provides pressure/flow at battery limits |
| DEL-02.01 | Line List provides line designations and specifications |
| DEL-02.03 | Tie-In List coordinates interface points and activities |
| DEL-00.05 | Interface Management Plan governs overall interface management |
| DEL-00.06 | Interface Register/Schedule tracks interface status |

### 5.3 Applicable Standards

| Standard | Description |
|----------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems |
| ASME B31.4 | Pipeline Transportation Systems for Liquids and Slurries |
| ASME B16.5 | Pipe Flanges and Flanged Fittings |
| TM Standards | Trans Mountain project-specific standards (to be confirmed) |

---

*End of Datasheet*
