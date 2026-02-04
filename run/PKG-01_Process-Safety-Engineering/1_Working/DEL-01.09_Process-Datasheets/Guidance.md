# Guidance: DEL-01.09 Process Datasheets

**Document ID:** DEL-01.09-GD
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides recommendations and best practices for developing Process Datasheets for the Puget Sound Optimization project. Process datasheets serve as the primary interface between Process Engineering and the Mechanical and Instrumentation disciplines, providing essential process data for equipment specification, procurement, and installation.

### 1.2 Target Audience

- Process Engineers (lead and supporting)
- Mechanical Engineers
- Instrumentation and Controls Engineers
- Procurement Specialists
- Project Engineers

---

## 2. Principles

### 2.1 Foundational Principles

| Principle | Description |
|-----------|-------------|
| Completeness | All required process data must be provided; no gaps for mechanical/I&C |
| Accuracy | Data must be derived from validated calculations (DEL-01.04/05/06/07) |
| Consistency | Data must be consistent across related datasheets and source documents |
| Traceability | Data must reference source calculations/documents |
| Timeliness | Datasheets must be available when mechanical/I&C disciplines need them |

### 2.2 Interface Principles

| Principle | Application |
|-----------|-------------|
| Early Coordination | Engage mechanical/I&C disciplines early to confirm data requirements |
| Template Agreement | Confirm TM datasheet templates before populating |
| Iterative Updates | Plan for updates as design progresses (IFR/IFD/IFC) |

---

## 3. Considerations

### 3.1 Technical Considerations

#### 3.1.1 Operating Conditions

For each piece of equipment, define:
- **Normal Operating Conditions**: Expected steady-state operation
- **Minimum Operating Conditions**: Turndown, startup, shutdown
- **Maximum Operating Conditions**: Peak flow, upset conditions
- **Design Conditions**: Envelope for mechanical design

**ASSUMPTION:** Design temperature and pressure should envelope all credible operating scenarios including upsets.

#### 3.1.2 Equipment-Specific Considerations

**Booster Pumps:**
- Flow rate range (minimum continuous stable flow to design)
- Differential head/pressure at operating points (per DEL-01.07)
- NPSH available (from DEL-01.07 hydraulic analysis)
- Power consumption estimate (per DEL-01.04)
- Fluid properties at pump conditions (density, viscosity, vapor pressure)

**Control Valves:**
- Flow coefficient (Cv) requirements (per DEL-01.05)
- Pressure drop across valve at normal/min/max flow (per DEL-01.07)
- Inherent valve characteristic requirement
- Cavitation potential (Xf, Kc factors per ISA 75.01)
- Noise considerations

**Relief Devices (PRV/TRV):**
- Set pressure
- Required relieving capacity
- Backpressure conditions
- Reference to DEL-01.06 relief calculations

**Flow Meters:**
- Flow range (with turndown ratio)
- Accuracy requirements
- Line size and schedule (per DEL-01.05)
- Reference to SOW-0005 (dedicated discharge meters)

**Block Valves:**
- Pressure rating (per DEL-01.01 design conditions)
- Size (per DEL-01.05 line sizing)
- Material compatibility

**Instruments:**
- Measurement range
- Accuracy requirements
- Reference to SOW-0177 (preliminary instrument datasheets)

#### 3.1.3 Fluid Property Considerations

| Consideration | Recommendation |
|---------------|----------------|
| Blend Variability | Provide properties for Heavy, Light, and Blended fluids |
| Temperature Effects | Provide viscosity at multiple temperatures if significant |
| Corrosivity | Document any corrosive constituents for material selection |
| Vapor Pressure | Essential for NPSH and cavitation calculations |

### 3.2 Project Considerations

| Consideration | Recommendation |
|---------------|----------------|
| TM Templates | Obtain TM datasheet templates before starting |
| Tag Number Coordination | Confirm equipment tag numbers with DEL-01.03 P&IDs |
| SOW Requirements | Follow SOW-0119 (valves), SOW-0177 (instruments), SOW-0224 (complete datasheets) |
| Vendor Coordination | Identify long-lead equipment for early datasheet completion |
| FEED vs. Detailed | Preliminary datasheets for FEED (IFR/IFD); complete for detailed design (IFC) |

### 3.3 Quality Considerations

| Aspect | Recommendation |
|--------|----------------|
| Cross-Reference Check | Verify data against DEL-01.07 hydraulic analysis and DEL-01.04/05/06 calculations |
| Peer Review | Have datasheets reviewed by a second process engineer |
| Discipline Review | Mechanical/I&C should confirm data adequacy |
| Consistency Check | Check related datasheets for consistency (e.g., upstream/downstream equipment) |
| Source Traceability | Reference source documents (DEL-01.01/04/05/06/07) |

---

## 4. Trade-offs

### 4.1 Design Trade-offs

| Trade-off | Conservative | Optimized | Recommendation |
|-----------|--------------|-----------|----------------|
| Design Margin | High margin on all parameters | Targeted margin on critical parameters | Per TM standards; balance cost vs. safety |
| Temperature Range | Wide range | Narrow based on actual expected conditions | Include ambient variations and upsets |
| Corrosion Allowance | Larger | Smaller based on service | Per TM standards for crude service |

### 4.2 Data Presentation Trade-offs

| Trade-off | Detailed | Summary | Recommendation |
|-----------|----------|---------|----------------|
| Fluid Properties | Full property table | Key properties only | Per TM template requirements; include density, viscosity, vapor pressure minimum |
| Operating Cases | All cases on datasheet | Reference to analysis | Key cases on datasheet; reference DEL-01.07 for details |
| Notes | Extensive notes | Minimal notes | Include critical notes; avoid excessive detail |

### 4.3 Timing Trade-offs

| Trade-off | Early Release | Late Release | Recommendation |
|-----------|---------------|--------------|----------------|
| FEED Phase (IFR/IFD) | Preliminary values (TBD acceptable) | Complete values (delays mechanical) | Issue preliminary with TBD at IFR; complete for IFD |
| Detailed Design (IFC) | Issue early with vendor-estimated data | Wait for certified vendor data | Issue at IFD with preliminary vendor data; update for IFC with certified data |

---

## 5. Examples

### 5.1 Process Datasheet Content (Typical Pump)

```
PROCESS DATASHEET - CENTRIFUGAL PUMP

1. General Information
   - Tag Number: P-XXX
   - Service: Booster Pump
   - P&ID Reference: XXX-PID-XXX (DEL-01.03)

2. Process Conditions
                        Normal    Min      Max      Design
   Suction Pressure     XXX kPag  XXX      XXX      XXX
   Discharge Pressure   XXX kPag  XXX      XXX      XXX
   Temperature          XXX degC  XXX      XXX      XXX
   Flow Rate            XXX m3/h  XXX      XXX      ---

3. Differential Head/Pressure
   Differential Head    XXX m     XXX      XXX      ---

4. NPSH Available       XXX m     XXX      XXX      ---

5. Fluid Properties (at normal operating temp)
   Density              XXX kg/m3
   Viscosity            XXX cSt
   Vapor Pressure       XXX kPa

6. References
   - DEL-01.04: Equipment sizing (pump capacity)
   - DEL-01.07: Hydraulic analysis (operating points, NPSH)

7. Notes
   - VFD controlled per SOW requirements
   - Material selection per crude service requirements
```

### 5.2 Process Datasheet Content (Typical Control Valve)

```
PROCESS DATASHEET - CONTROL VALVE

1. General Information
   - Tag Number: FCV-XXX
   - Service: Flow Control
   - P&ID Reference: XXX-PID-XXX (DEL-01.03)

2. Process Conditions
                        Normal    Min      Max      Shutoff
   Inlet Pressure       XXX kPag  XXX      XXX      XXX
   Outlet Pressure      XXX kPag  XXX      XXX      XXX
   Pressure Drop        XXX kPa   XXX      XXX      XXX
   Temperature          XXX degC  XXX      XXX      XXX
   Flow Rate            XXX m3/h  XXX      XXX      ---

3. Fluid Properties
   Density              XXX kg/m3
   Viscosity            XXX cSt
   Vapor Pressure       XXX kPa

4. Sizing Data
   Required Cv          XXX       XXX      XXX
   Line Size            XXX" (per DEL-01.05)
   Valve Size           XXX" (mechanical selection)

5. References
   - DEL-01.05: Line sizing (valve sizing basis)
   - DEL-01.07: Hydraulic analysis (operating conditions)

6. Notes
   - Check cavitation potential per ISA 75.01
```

### 5.3 Process Datasheet Content (Typical Relief Valve)

```
PROCESS DATASHEET - RELIEF VALVE

1. General Information
   - Tag Number: PRV-XXX
   - Service: Overpressure Protection
   - P&ID Reference: XXX-PID-XXX (DEL-01.03)

2. Set Pressure and Relieving Conditions
   Set Pressure         XXX kPag
   Relieving Pressure   XXX kPag
   Relieving Capacity   XXX kg/h
   Temperature          XXX degC

3. Backpressure
   Built-up             XXX kPag
   Superimposed         XXX kPag

4. Fluid Properties
   Density              XXX kg/m3
   Viscosity            XXX cSt

5. References
   - DEL-01.06: Relief calculations (sizing basis)
   - DEL-01.01: DBM (design pressure)

6. Notes
   - API 526 sizing per DEL-01.06
```

### 5.4 Common Pitfalls to Avoid

- Missing NPSH available for pumps (critical for mechanical design)
- Missing vapor pressure for cavitation evaluation
- Inconsistent units across datasheets
- Not updating datasheets when calculations change
- Incomplete minimum operating conditions
- Not considering viscosity effects on pump performance
- Tag numbers not matching P&IDs (DEL-01.03)
- Missing references to source calculations (DEL-01.04/05/06/07)
- Not coordinating with mechanical/I&C disciplines early

---

## 6. Additional Resources

### 6.1 Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.01 Guidance | DBM provides design basis |
| DEL-01.04 Guidance | Equipment sizing provides pump/vessel sizing |
| DEL-01.05 Guidance | Line sizing provides valve sizing |
| DEL-01.06 Guidance | Relief calculations provide relief device sizing |
| DEL-01.07 Guidance | Hydraulic analysis provides operating data |

### 6.2 Related SOW Requirements

| SOW Item | Description |
|----------|-------------|
| SOW-0119 | Produce FEED mechanical/electrical datasheets for valves |
| SOW-0177 | Develop preliminary instrument datasheets |
| SOW-0224 | Complete remaining process datasheets |
| SOW-0005 | Dedicated discharge flow meters |

### 6.3 Industry References

| Reference | Application |
|-----------|-------------|
| API 610 | Pump datasheet format |
| API 526 | Relief valve datasheet format |
| API 650 | Tank datasheet format (if applicable) |
| ISA 75.01 | Control valve sizing data |
| ISA 20 | Instrument specification forms |
| IEC 60534 | Control valve specifications |

---

*End of Guidance*
