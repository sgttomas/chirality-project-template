# Guidance: DEL-01.04 Equipment Sizing Calculations

**Document ID:** DEL-01.04-GD
**Revision:** Phase 2.2 (PASS2-COMPLETE)
**Date:** 2026-02-01
**Status:** PASS2-COMPLETE

---

## Purpose

### Document Intent

This guidance document provides recommendations and best practices for developing Equipment Sizing Calculations for the Puget Sound Optimization (PSO) project. It supplements the formal specification with practical considerations for sizing booster pumps, VFDs, flow meters, and manifold equipment at Sumas Tank Farm.

### Target Audience

- Process Engineers (lead and supporting)
- Mechanical Engineers
- I&C Engineers
- Engineering Managers

---

## Principles

### Foundational Principles

| Principle | Description |
|-----------|-------------|
| Design Basis Traceability | All sizing must trace to DEL-01.01 (DBM) parameters |
| Conservative Sizing | Apply appropriate safety factors while remaining cost-effective |
| Verification Focus | Verify and finalize preliminary sizing per SOW §2.3.1.6 |
| Coordination | Coordinate with DEL-01.05 (Line Sizing) and DEL-01.07 (Hydraulic Analysis) |
| Documentation | Document all assumptions, sources, and TBDs clearly |

### PSO-Specific Considerations

| Consideration | Application | Source |
|---------------|-------------|--------|
| Peak Flow Sizing | Size all equipment for 315,000 bpd (2,100 m³/h) | SOW §2.2.1 |
| Pump Configuration | 2 large + 2 small + 1 medium capacity VS6 pumps (5 total) | SOW §2.3.1.2 |
| VFD Per Pump | Each of 5 pumps requires individual VFD | SOW §2.3.1.4 |
| Flow Metering | Dedicated discharge flow meter per pump (5 total) | SOW §2.3.1.4 |
| Blending Control | Flow ratio control between heavy and light | SOW §2.3.1.4 |
| Manifold | 5x6 configuration | SOW §2.3.1.1 |

---

## Considerations

### Technical Considerations

#### Booster Pump Sizing

Per SOW §2.3.1.1-2:

| Pump Type | Quantity | Sizing Approach |
|-----------|----------|-----------------|
| Large Capacity | 2 | Size for major portion of peak flow |
| Small Capacity | 2 | Size for flexibility and blending control |
| Medium Capacity | 1 | Size for intermediate duty |

Key sizing parameters:
- Flow Rate (Q): Allocate peak 315,000 bpd (2,100 m³/h) among 5 pumps per operating philosophy
- Total Dynamic Head (TDH): From DEL-01.07 (Hydraulic Analysis)
- NPSH Available: Based on tank suction conditions from DEL-01.07
- Efficiency: Per API 610 and vendor curves
- **ASSUMPTION:** VS6-type pumps are vertically suspended - confirm specific model with TM

#### VFD Sizing

Per SOW §2.3.1.4, each pump requires VFD (5 total):

| Parameter | Consideration |
|-----------|---------------|
| Motor HP | Based on pump hydraulic power + efficiency losses |
| Speed Range | Based on turndown requirements (sustainable to peak) |
| Turndown Capability | Support blending ratio variations |
| Voltage/Frequency | Per site electrical system (coordinate with PKG-06) |

#### Flow Meter Sizing

Per SOW §2.3.1.4, dedicated discharge flow meter per pump (5 total):

| Parameter | Consideration |
|-----------|---------------|
| Flow Range | Individual pump flow at minimum to maximum speed |
| Rangeability | **ASSUMPTION:** Minimum 10:1 for blending control |
| Accuracy | Per blending control requirements |
| Meter Type | **TBD** - Coordinate with I&C (Coriolis, ultrasonic, turbine) |

#### Manifold Header Sizing

Per SOW §2.3.1.1, 5x6 manifold:

| Parameter | Consideration |
|-----------|---------------|
| Velocity Limit | **ASSUMPTION:** 3-5 m/s for liquid hydrocarbon |
| Pressure Drop | Minimize to preserve pump head |
| Configuration | **ASSUMPTION:** 5 inlet, 6 outlet (confirm with TM) |

#### Auxiliary Equipment Sizing

Per SOW §3.2.3.10:

| Equipment | Sizing Basis |
|-----------|--------------|
| Sump Tank | Drainage/containment volume requirements |
| Reinjection Pumps | Sump drainage flow and head requirements |

### Integration Considerations

| Integration Point | Recommendation |
|-------------------|----------------|
| DEL-01.01 (DBM) | Source for design basis, fluid properties, flow rates |
| DEL-01.05 (Line Sizing) | Coordinate header and line sizes |
| DEL-01.07 (Hydraulic Analysis) | Source for TDH, NPSH, system curve |
| Appendix C Hydraulic Report | Reference for preliminary hydraulic data |
| DEL-01.09 (Process Datasheets) | Output destination for sizing results |
| DEL-00.01 (MDR) | Register final calculations |
| PKG-03 Mechanical | Coordinate equipment specifications |
| PKG-06 Electrical | Coordinate VFD and motor requirements |
| PKG-07 I&C | Coordinate flow meter selection |

---

## Trade-offs

### Design Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Pump Sizing Margin | 15-20% (conservative) | 10% (optimized) | **ASSUMPTION:** 10-15% pending TM guidance |
| Pump Configuration | Equal capacity (5 x 20%) | Mixed capacity (2L+2S+1M) | Mixed per SOW §2.3.1.2 |
| VFD Speed Range | Wide range (50-100%) | Narrow range (80-100%) | Wide range for blending flexibility |
| Flow Meter Type | Coriolis (high accuracy) | Ultrasonic (lower cost) | **TBD** - Per I&C and TM input |

### Sizing Trade-offs

| Trade-off | Larger Equipment | Smaller Equipment | Recommendation |
|-----------|------------------|-------------------|----------------|
| Pump Size | More margin, higher capital | Less margin, risk of undersizing | Size for peak (315,000 bpd) with appropriate margin |
| Manifold Headers | Lower velocity, lower dP | Higher velocity, higher dP | Balance velocity limits (3-5 m/s) with cost |

### Risk Considerations

| Risk | Mitigation |
|------|------------|
| Incomplete hydraulic data from DEL-01.07 | Document assumptions; flag for update |
| Blending range uncertainty (SOW vs DBM) | Size for wider range until confirmed |
| Preliminary sizing differs from calculations | Document differences; obtain TM approval |
| Fluid property variations | Apply appropriate safety factors |

---

## Examples

### Example 1: Pump Sizing Summary Table

```
| Pump Tag | Capacity | Design Flow | TDH | NPSHa | Motor HP | VFD Range |
|----------|----------|-------------|-----|-------|----------|-----------|
| P-XXX-A  | Large    | TBD m³/h    | TBD | TBD   | TBD      | TBD%      |
| P-XXX-B  | Large    | TBD m³/h    | TBD | TBD   | TBD      | TBD%      |
| P-XXX-C  | Small    | TBD m³/h    | TBD | TBD   | TBD      | TBD%      |
| P-XXX-D  | Small    | TBD m³/h    | TBD | TBD   | TBD      | TBD%      |
| P-XXX-E  | Medium   | TBD m³/h    | TBD | TBD   | TBD      | TBD%      |
| TOTAL    | -        | 2,100 m³/h  | -   | -     | -        | -         |
```

### Example 2: Calculation Report Structure

```
1. Introduction and Scope
2. Design Basis Summary (from DEL-01.01 DBM)
   2.1 Flow Rates (315,000 bpd peak / 2,100 m³/h)
   2.2 Fluid Properties
   2.3 Design Conditions
3. Hydraulic Data (from DEL-01.07 Hydraulic Analysis)
   3.1 System Curve
   3.2 NPSH Available
   3.3 Operating Points
4. Booster Pump Sizing
   4.1 Large Capacity Pumps (2)
   4.2 Small Capacity Pumps (2)
   4.3 Medium Capacity Pump (1)
   4.4 Pump Selection Summary
5. VFD Sizing (5 units per SOW §2.3.1.4)
   5.1 Motor Requirements
   5.2 Speed Range
   5.3 VFD Selection Summary
6. Flow Meter Sizing (5 units per SOW §2.3.1.4)
   6.1 Flow Range per Pump
   6.2 Accuracy Requirements
   6.3 Meter Type Selection
7. Manifold Header Sizing (5x6 configuration)
   7.1 Velocity Calculations
   7.2 Pressure Drop Calculations
8. Auxiliary Equipment Sizing (per SOW §3.2.3.10)
   8.1 Sump Tank
   8.2 Reinjection Pumps
9. Assumptions and TBDs
10. References
Appendix A: Calculation Sheets
Appendix B: Vendor Data (as available)
```

### Example 3: Assumption Documentation Format

```
ASSUMPTION: The large capacity pumps are assumed to handle 40% each of peak
flow (840 m³/h each) based on typical pump station configurations.

Basis: Industry practice for multi-pump stations with mixed capacities
Impact: Determines pump hydraulic requirements and motor sizing
Action Required: Confirm pump duty allocation with TM and DEL-01.07 hydraulic analysis
Status: OPEN - Pending DEL-01.07 completion
```

### Example 4: Cross-Reference Verification

```
Parameter Verification:
- Peak Flow Rate: 315,000 bpd (2,100 m³/h) per SOW §2.2.1 ✓
- Pump Quantity: 5 VS6-type per SOW §2.3.1.1 ✓
- Pump Configuration: 2L+2S+1M per SOW §2.3.1.2 ✓
- VFD Quantity: 5 (one per pump) per SOW §2.3.1.4 ✓
- Flow Meter Quantity: 5 (one per pump discharge) per SOW §2.3.1.4 ✓
- Manifold: 5x6 configuration per SOW §2.3.1.1 ✓
- Design Basis: Per DEL-01.01 (DBM) ✓
- Hydraulic Data: Per DEL-01.07 (Hydraulic Analysis) ✓
```

---

## Additional Resources

### Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.01 Guidance | Design basis parameters - input source |
| DEL-01.05 Guidance | Line sizing coordination |
| DEL-01.07 Guidance | Hydraulic analysis - TDH and NPSH source |
| DEL-01.09 Guidance | Process datasheets - output from sizing |

### Coordination Checklist

- [ ] Obtain design basis from DEL-01.01 (DBM)
- [ ] Obtain hydraulic data from DEL-01.07 (concurrent development)
- [ ] Review Appendix C Hydraulic Report for preliminary data
- [ ] Confirm pump configuration with TM (2L+2S+1M per SOW §2.3.1.2)
- [ ] Confirm 5 VFDs required per SOW §2.3.1.4
- [ ] Confirm 5 flow meters required per SOW §2.3.1.4
- [ ] Coordinate with PKG-03 for mechanical equipment specifications
- [ ] Coordinate with PKG-06 for electrical/VFD requirements
- [ ] Coordinate with PKG-07 for flow meter selection
- [ ] Verify preliminary sizing from existing engineering per SOW §2.3.1.6
- [ ] Document all assumptions and TBDs
- [ ] Register in MDR per DEL-00.01

---

*End of Guidance*
