# Datasheet: DEL-01.09 Process Datasheets

**Document ID:** DEL-01.09-DS
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.09 |
| Deliverable Name | Process Datasheets |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Data Sheet |
| Responsible Party | Engineering Contractor |

---

## 2. Attributes

### 2.1 Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Project Phase | FEED + Detailed Design | Per decomposition |
| Datasheet Purpose | Provide process data for mechanical and instrumentation equipment | Per SOW-0224 |
| Applicable Equipment | Pumps, valves, instruments, tanks/vessels, packaged equipment | Including packaged components |
| Format Standard | **TBD** | **ASSUMPTION:** TM datasheet templates or API/ISA standards |

### 2.2 Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | Datasheet set (all equipment) |
| Native Format | Excel or Word (editable) |
| Deliverable Format | PDF + Native editable files |
| Revision Cycle | IFR (Rev A) -> IFD (Rev 0) -> IFC (Rev 1) |

### 2.3 Datasheet Categories

| Category | Equipment Types | Estimated Count | Notes |
|----------|-----------------|-----------------|-------|
| Rotating Equipment | Booster pumps, sump pumps, reinjection pumps | **TBD** (min 5+2+2) | Per DEL-01.04 |
| Control Valves | Flow control valves, blending valves | **TBD** | Per DEL-01.05 |
| Block Valves | Isolation valves, manifold valves | **TBD** | Per P&IDs |
| Relief Devices | PRVs, TRVs | **TBD** | Per DEL-01.06 |
| Flow Meters | Dedicated discharge meters | **TBD** | Per SOW-0005 |
| Instruments (Process Data) | Pressure transmitters, temperature | **TBD** | Per SOW-0177 |
| Tanks/Vessels | Sump tank | **TBD** | If applicable |

---

## 3. Conditions

### 3.1 Process Conditions (Typical Ranges)

| Parameter | Min | Normal | Max | Notes |
|-----------|-----|--------|-----|-------|
| Operating Pressure | **TBD** kPag | **TBD** kPag | **TBD** kPag | Per DEL-01.07 hydraulic analysis |
| Design Pressure | N/A | **TBD** kPag | N/A | Per DEL-01.01 DBM |
| Operating Temperature | **TBD** deg C | **TBD** deg C | **TBD** deg C | Per fluid conditions |
| Design Temperature | **TBD** deg C | **TBD** deg C | **TBD** deg C | Per DEL-01.01 DBM |
| Flow Rate | **TBD** m3/h | 1,822 m3/h | 2,100 m3/h | Per SOW-0002 |

### 3.2 Fluid Properties (Reference)

| Property | Heavy Crude | Light Crude | Blended | Notes |
|----------|-------------|-------------|---------|-------|
| Density | **TBD** kg/m3 | **TBD** kg/m3 | **TBD** kg/m3 | At operating conditions |
| Viscosity | **TBD** cSt | **TBD** cSt | **TBD** cSt | At operating conditions |
| Vapor Pressure | **TBD** kPa | **TBD** kPa | **TBD** kPa | For NPSH and cavitation |
| Blend Range | 20% | 80% | 100% | Per SOW; 10%-100% per DBM |
| Corrosivity | **TBD** | **TBD** | **TBD** | For material selection |

### 3.3 Equipment-Specific Process Data

| Equipment Category | Key Process Parameters | Source |
|--------------------|----------------------|--------|
| Booster Pumps | Flow, head, NPSH available, power | DEL-01.04 + DEL-01.07 |
| Control Valves | Cv, dP, flow range, cavitation factors | DEL-01.05 + DEL-01.07 |
| Flow Meters | Flow range, accuracy, line size | SOW-0005 + DEL-01.05 |
| Relief Devices | Set pressure, relieving rate, backpressure | DEL-01.06 |
| Block Valves | Pressure rating, size | DEL-01.05 + DEL-01.03 |
| Instruments | Measurement range, accuracy | SOW-0177 + DEL-01.03 |

---

## 4. Construction

### 4.1 Datasheet Content Requirements

Each process datasheet shall include:
- Equipment tag number and description
- P&ID reference (DEL-01.03)
- Service description
- Process conditions (normal, min, max, design)
- Fluid properties at operating conditions
- Material compatibility requirements
- Hazardous area classification
- Special requirements (noise, VFD control, etc.)
- Referenced specifications/standards

### 4.2 Datasheet Types and Templates

| Equipment Type | Template Standard | Notes |
|----------------|-------------------|-------|
| Centrifugal Pumps | API 610 / TM Standard | **TBD** - Confirm template with TM |
| Control Valves | ISA 75.01 / IEC 60534 / TM | **TBD** |
| Block Valves | TM Standard | **TBD** |
| Relief Valves | API 526 / TM | **TBD** |
| Flow Meters | ISA 20 / TM Standard | **TBD** |
| Instruments | ISA 20 / TM Standard | **TBD** |
| Tanks/Vessels | API 650 / TM | **TBD** - If applicable |

### 4.3 Dependencies

| Dependency | Source | Status Required | Purpose |
|------------|--------|-----------------|---------|
| Design Basis (DBM) | DEL-01.01 | IFR minimum | Design conditions |
| Process Flow Diagrams | DEL-01.02 | IFR minimum | Process context |
| P&IDs | DEL-01.03 | IFR minimum | Tag numbers and references |
| Equipment Sizing | DEL-01.04 | Required | Pump/vessel capacity data |
| Line Sizing | DEL-01.05 | Required | Valve sizing, line data |
| Relief Calculations | DEL-01.06 | Required (relief devices) | Relief device sizing |
| Hydraulic Analysis | DEL-01.07 | Required | Operating conditions |
| TM Datasheet Templates | TM | Required | Standard format |

---

## 5. References

### 5.1 Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0119: Produce FEED mechanical/electrical datasheets for valves (incl check valves/actuators) |
| SOW Reference | SOW-0177: Develop preliminary instrument datasheets |
| SOW Reference | SOW-0224: Complete remaining process datasheets and supply process data for mechanical and instrumentation equipment |
| SOW Reference | SOW-0005: Dedicated discharge flow meters |
| SOW Reference | SOW-0002: Design basis flow rates |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### 5.2 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | DBM provides design conditions basis |
| DEL-01.02 | PFDs show equipment in process context |
| DEL-01.03 | P&IDs provide equipment tag numbers |
| DEL-01.04 | Equipment sizing provides capacity data |
| DEL-01.05 | Line sizing provides line/valve data |
| DEL-01.06 | Relief calcs provide relief device data |
| DEL-01.07 | Hydraulic analysis provides operating data |
| DEL-01.16 | Material requisitions reference datasheets |
| DEL-03.xx | Mechanical datasheets (mechanical discipline) |
| DEL-07.xx | Instrument datasheets (I&C discipline) |

### 5.3 Applicable Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| API 610 | Centrifugal Pumps for Petroleum, Petrochemical and Natural Gas Industries | Pump datasheet format |
| API 526 | Flanged Steel Pressure-relief Valves | Relief valve datasheet format |
| API 650 | Welded Tanks for Oil Storage | Tank datasheet format (if applicable) |
| ISA 75.01 | Flow Equations for Sizing Control Valves | Control valve sizing data |
| ISA 20 | Specification Forms for Process Measurement and Control Instruments | Instrument datasheet format |
| IEC 60534 | Industrial-process control valves | Control valve specifications |
| TM Standards | Trans Mountain project-specific templates | Project-specific format (**TBD**) |

---

*End of Datasheet*
